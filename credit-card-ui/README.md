# Credit Card UI Design

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is a clean and modern credit card UI created using only HTML and CSS. It showcases a realistic front-face of a credit card with a stylish background, logo, and cardholder details. It serves as a great example of CSS for layout, styling, and positioning.

## Features

*   **Modern & Clean Design:** A visually appealing credit card design with a custom background image.
*   **Realistic Details:** Includes common credit card elements like a logo, chip, card number, cardholder name, and expiration date.
*   **Pure CSS & HTML:** Built without any JavaScript, making it lightweight, fast, and easy to understand.
*   **Responsive:** The card is designed to be responsive and maintains its layout on different screen sizes.
*   **Easy to Customize:** The content and styling can be easily modified to fit different card types or branding.

## Technologies Used

*   HTML5
*   CSS3
*   [Google Fonts (Poppins)](https://fonts.google.com/specimen/Poppins) for typography.

## Project Structure

The HTML structure is simple, consisting of a single `.container` that acts as the card. Inside, a `<header>` holds the logo and chip, and a `.card-details` div contains the card number, name, and expiration date.

```html
<div class="container">
    <header>
        <span class="logo">
            <img src="images/logo.png" alt="Card Logo" />
            <h5>Master Card</h5>
        </span>
        <img src="images/chip.png" alt="Card Chip" class="chip" />
    </header>

    <div class="card-details">
        <div class="name-number">
            <h6>Card Number</h6>
            <h5 class="number">8050 5040 2030 3020</h5>
            <h5 class="name">Prem Kumar Shahi</h5>
        </div>
        <div class="valid-date">
            <h6>Valid Thru</h6>
            <h5>05/28</h5>
        </div>
    </div>
</div>
```

## Getting Started

1.  Clone the repository or download the source code.
2.  Open the `index.html` file in your web browser to view the card.

## Customization

You can easily customize the card's appearance by editing the `styles.css` file.

*   **Card Background:** Change the `background-image` property on the `.container` selector.
*   **Text Content:** Update the cardholder name, number, and date directly in the `index.html` file.
*   **Colors:** Modify the `color` properties for the `h5` and `h6` elements to change the text color.
*   **Logo:** Replace the `images/logo.png` and `images/chip.png` files with your own assets.

## Browser Compatibility

This project uses basic HTML and CSS and is compatible with all modern web browsers.

| Browser          | Supported |
| ---------------- | :-------: |
| Chrome           |    Yes    |
| Firefox          |    Yes    |
| Safari           |    Yes    |
| Edge             |    Yes    |
| Opera            |    Yes    |

## License

This project is licensed under the MIT License.
