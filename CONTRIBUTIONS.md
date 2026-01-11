# Contributing to Worded

Thanks for your interest in contributing to Worded. We welcome contributions from everyone to help make this the best offline Markdown editor available.

## How to Contribute

### Reporting Bugs

If you find a bug or a display issue (e.g., PDF margins appearing incorrect), please open an Issue in the repository. Be sure to include:

1. Which browser you are using.
2. A screenshot of the issue.
3. Steps to reproduce the error.

### Suggesting Enhancements

Have an idea for a new feature? We'd love to hear it. Please open an Issue and tag it as an "Enhancement".

### Pull Requests

We follow a standard GitHub workflow.

1. **Fork the repository** to your own GitHub account.
2. **Clone the project** to your machine.
3. **Create a branch** locally with a succinct name (e.g., `fix-pdf-margins` or `feature-dark-mode`).
4. **Commit changes** to the branch.
5. **Push changes** to your fork.
6. **Open a Pull Request** in our repository.

## Development Guidelines

* **No Build Steps:** This project is designed to run without Node.js build steps (Webpack/Vite) to keep it accessible. Please do not introduce complex build chains unless absolutely necessary.
* **Code Style:** Keep the HTML, CSS, and JS clean. Since the logic is contained within `index.html`, ensure comments are used liberally to separate the Logic, Styles, and Markup.
* **NZ English:** Please ensure all user-facing copy uses New Zealand English spelling (e.g., *Colour*, *Licence*, *Optimise*).

## Project Structure

* `index.html`: Contains the core application logic, styling, and markup.
* `*.js / *.css`: Local copies of CDN libraries (Quill, Tailwind, etc.) to ensure offline functionality.

Thank you for your help!
