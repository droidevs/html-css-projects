# Flipping Card UI

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project showcases a dynamic and interactive flipping card UI created with pure HTML and CSS. It's an excellent example of using CSS3 transitions and transforms to create an engaging user experience without needing JavaScript. When a user hovers over the card, it performs a 3D flip to reveal content on the back.

## Features

*   **3D Flip Animation:** A smooth, eye-catching 3D flip effect on hover, achieved using `transform` and `transition`.
*   **Pure CSS:** The entire animation is achieved with CSS, making it lightweight and performant.
*   **Front & Back Content:** Each card has a distinct front and back side, perfect for showing a summary on the front and details on the back.
*   **Responsive Design:** The card is built to be responsive and will adapt to various screen sizes.
*   **Easy to Customize:** The content, styling, and animation can be easily modified.
*   **Accessibility Friendly:** Includes considerations for users who prefer reduced motion.

## Technologies Used

*   HTML5
*   CSS3

## Project Structure

The basic HTML structure consists of a container for the card, an inner element to handle the 3D transformation, and the front and back faces. The `transform-style: preserve-3d` property on the inner container is key to making the 3D effect work.

```html
<div class="flip-card">
  <div class="flip-card-inner">
    <div class="flip-card-front">
      <!-- Content for the front of the card -->
      <h1>Front Side</h1>
    </div>
    <div class="flip-card-back">
      <!-- Content for the back of the card -->
      <h1>Back Side</h1>
    </div>
  </div>
</div>
```

## Getting Started

1.  Clone the repository or download the source code.
    ```bash
    git clone [your-repository-url]
    ```
2.  Open the `index.html` file in your web browser.
3.  Hover over the card to see the flip effect.

## Customization

You can easily customize the card's appearance and behavior by editing the `styles.css` file.

*   **Colors:** Change the `background-color` for `.flip-card-front` and `.flip-card-back`.
*   **Dimensions:** Adjust the `width` and `height` of the `.flip-card` class.
*   **Flip Speed:** Modify the `transition` duration on the `.flip-card-inner` class.
*   **Flip Direction:** To change from a horizontal to a vertical flip, update the `transform` property from `rotateY(180deg)` to `rotateX(180deg)`.

## Browser Compatibility

This project uses CSS 3D Transforms, which are widely supported by all modern web browsers. The `backface-visibility: hidden;` property is used to hide the reverse side of an element when it is facing away from the user.

| Browser          | Supported |
| ---------------- | :-------: |
| Chrome           |    Yes    |
| Firefox          |    Yes    |
| Safari           |    Yes    |
| Edge             |    Yes    |
| Opera            |    Yes    |

## Accessibility

To respect users' motion preferences, the `prefers-reduced-motion` media query can be used to disable the animation for those who have this setting enabled in their operating system. Instead of a flip, a simple fade can be used.

```css
@media (prefers-reduced-motion: reduce) {
  .flip-card-inner {
    transition: opacity 0.5s;
  }
  .flip-card:hover .flip-card-inner {
    transform: none;
  }
}
```

## License

This project is licensed under the MIT License.