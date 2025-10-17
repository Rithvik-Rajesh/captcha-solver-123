# CAPTCHA Solver Demo

A simple, client-side demonstration of a CAPTCHA input and validation system. This application is designed to showcase basic HTML structure, responsive design with Tailwind CSS, and client-side JavaScript for handling user input and image loading.

## Features

-   **Responsive Design**: Built with Tailwind CSS for optimal viewing across various devices.
-   **Image Loading**: Displays a CAPTCHA image. Defaults to `sample.png` but can load external images via URL query parameter.
-   **User Input**: Provides an input field for users to enter the CAPTCHA text.
-   **Client-side Validation**: Includes a basic client-side validation logic (for demonstration purposes, hardcoded to "ADUR3" for `sample.png`).

## Usage

To run this application, simply open the `index.html` file in your web browser.

### Loading Custom CAPTCHA Images

You can specify a custom image URL for the CAPTCHA by appending a `?url=` query parameter to the `index.html` path.

**Example:**
`index.html?url=https://example.com/path/to/your-captcha-image.png`

If no `url` parameter is provided, the application will default to displaying `sample.png`.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS**: For utility-first styling and responsive design.
-   **JavaScript**: For dynamic content, URL parameter handling, and CAPTCHA validation logic.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
