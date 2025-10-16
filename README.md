# Captcha Solver Frontend Demo

A simple, responsive web application designed to demonstrate a basic frontend for a captcha solver. It allows users to view a captcha image and enter the corresponding text. The application dynamically loads captcha images based on URL parameters or defaults to a provided sample image.

## Features

-   **Dynamic Image Loading**: Loads captcha images from a `url` query parameter. Example: `index.html?url=https://example.com/your-captcha.png`
-   **Default Image**: If no `url` parameter is provided, it defaults to `sample.png`.
-   **User Input**: Provides a text field for users to enter the captcha solution.
-   **Responsive Design**: Built with Tailwind CSS for a modern and responsive user interface.
-   **Client-Side Feedback**: Displays the entered text upon submission (no actual backend validation in this demo).

## Usage

1.  **Clone the Repository (or save files locally)**:

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  **Open `index.html`**: Simply open the `index.html` file in your web browser.

    -   The application will display the `sample.png` image by default, which reads "ADUR3".

3.  **Load Custom Captcha Image**: To test with a different captcha image, append a `?url=` query parameter to your browser's URL. Replace `YOUR_IMAGE_URL` with the direct link to your image.

    Example:
    `file:///path/to/your/index.html?url=https://example.com/your-new-captcha.png`

4.  **Enter Captcha**: Type the text you see in the captcha image into the input field.

5.  **Submit**: Click the "Submit Captcha" button. The entered text will be displayed below the button.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS**: For styling and responsive design.
-   **JavaScript**: For dynamic image loading and handling user interaction.

## Installation

No special installation steps are required beyond opening the `index.html` file in a modern web browser. Ensure `sample.png` is in the same directory as `index.html`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
