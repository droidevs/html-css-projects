# Profile Card UI Design

This project is a responsive and modern Profile Card created using only HTML and CSS. It's designed to showcase user information in a clean, visually appealing layout, perfect for personal portfolios, team pages, or contact displays.

## Features

*   **Responsive Design:** The card layout adapts smoothly to various screen sizes.
*   **Modern UI:** Features a clean design with a colored header, rounded corners, and subtle shadows.
*   **Social Media Links:** Includes icon buttons for linking to social media profiles.
*   **Interactive Elements:** Hover effects on buttons provide user feedback.
*   **Pure CSS & HTML:** Built without any JavaScript, making it lightweight and fast.
*   **Easy to Customize:** The content and styling can be easily modified to fit your project's needs.

## Technologies Used

*   HTML5
*   CSS3
*   [Google Fonts](https://fonts.google.com/specimen/Poppins) for typography.
*   [Boxicons](https://boxicons.com/) for icons.

## How to Use

1.  Clone the repository or download the source code.
2.  Open the `index.html` file in your web browser.
3.  Customize the profile information directly in the `index.html` file (e.g., change the profile image, name, and job title).
4.  Modify the styles in `styles.css` to change the color scheme, fonts, or spacing. The main color can be changed by updating the `background-color` of `.profile-card::before` and `.buttons .button`.

## Project Structure

The HTML structure is centered around a main `.profile-card` container which holds all the elements for the image, text data, buttons, and analytics.

```html
<div class="profile-card">
    <div class="image">
        <img src="profile.jpeg" alt="" class="profile-img" />
    </div>

    <div class="text-data">
        <span class="name">CodingLab</span>
        <span class="job">Youtuber & Blogger</span>
    </div>

    <div class="media-buttons">
        <!-- Social media links -->
    </div>

    <div class="buttons">
        <button class="button">Subscribe</button>
        <button class="button">Message</button>
    </div>

    <div class="analytics">
        <!-- Stats like likes, comments, shares -->
    </div>
</div>
```