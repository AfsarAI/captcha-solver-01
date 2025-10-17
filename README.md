# Dark-themed CAPTCHA Solver

This project provides a simple, single-page web application for demonstrating a CAPTCHA verification process with a dark aesthetic. It features a customizable CAPTCHA image display, user input field, and a dynamic "Verify" button that provides instant feedback on the verification attempt.

## Features

*   **Dark Theme:** A modern, eye-pleasing dark interface.
*   **CAPTCHA Display:** Presents a static CAPTCHA image for user recognition.
*   **User Input:** An input field for users to type in the CAPTCHA text.
*   **Interactive Verify Button:** A circular "Verify" button with a subtle hover animation.
*   **Instant Feedback:** Displays a clear success or failure message after verification.
*   **Responsive Design:** Adapts gracefully to different screen sizes.

## How to Run/Test

To get this CAPTCHA solver running on your local machine, follow these simple steps:

1.  **Save the files:**
    *   Save the provided `index.html` content into a file named `index.html`.
    *   Ensure the CAPTCHA image is available. The application expects an image file named `image.png` (which refers to the `captcha-sample.png` you provided) in the same directory as `index.html`.
2.  **Open in Browser:**
    *   Simply open the `index.html` file in your preferred web browser.

That's it! The application is entirely client-side, so no server setup or build process is required.

## Technologies Used

*   **HTML5:** For the page structure.
*   **Tailwind CSS (CDN):** For utility-first styling and responsive design.
*   **JavaScript:** For client-side CAPTCHA verification logic.

## CAPTCHA Value

For demonstration purposes, the correct CAPTCHA text is hardcoded within the `index.html` JavaScript. Based on the `image.png`, the correct value is `V4XBG`. The verification is case-insensitive.
