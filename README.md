# Captcha Solver

## Summary

The Captcha Solver is a web application designed to automatically solve CAPTCHA images provided via a URL parameter. It retrieves the image from the specified URL, processes it, and displays the solved text on the page within 15 seconds. This project aims to simplify the CAPTCHA solving process for developers and users alike.

## Setup & Usage Instructions

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (version 14 or higher)
- npm (Node Package Manager)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/captcha-solver.git
   cd captcha-solver
   ```

2. Install the required dependencies:

   ```bash
   npm install
   ```

### Running the Application

To start the application, run the following command:

```bash
npm start
```

The application will be available at `http://localhost:3000`.

### Using the Application

To use the CAPTCHA solver, navigate to the following URL format in your web browser:

```
http://localhost:3000/?url=https://example.com/image.png
```

Replace `https://example.com/image.png` with the URL of the CAPTCHA image you want to solve. If no URL is provided, the application will default to a sample CAPTCHA image included in the project.

The solved CAPTCHA text will be displayed on the page within 15 seconds.

## Explanation of Key Files

- **app.js**: The main application file where the server is set up and routes are defined.
- **captchaSolver.js**: Contains the logic for fetching the CAPTCHA image from the provided URL and solving it using image processing techniques.
- **public/index.html**: The HTML file that serves as the frontend interface for the application, displaying the CAPTCHA image and the solved text.
- **package.json**: Lists the project dependencies and scripts for running the application.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Feel free to contribute to this project by submitting issues or pull requests. Your feedback and contributions are welcome!