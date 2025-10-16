# Markdown to HTML Converter

![GitHub last commit](https://img.shields.io/github/last-commit/gmahesh-09/markdown-to-html)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Repository:** [https://github.com/gmahesh-09/markdown-to-html](https://github.com/gmahesh-09/markdown-to-html)
**Live Demo:** [https://gmahesh-09.github.io/markdown-to-html/](https://gmahesh-09.github.io/markdown-to-html/)

## Project Overview

This project provides a simple, client-side static web application designed to convert Markdown content into rendered HTML. It specifically processes an `input.md` file, which users can provide via a standard file attachment input. The application seamlessly integrates `marked.js` for robust Markdown parsing and `highlight.js` to ensure all code blocks within the Markdown are beautifully and accurately syntax-highlighted. The resulting HTML is then dynamically displayed within a designated output area on the web page.

## Features

*   **Client-Side Conversion**: All Markdown parsing and HTML generation occur directly within the user's browser, eliminating the need for a backend server.
*   **File Input Support**: Enables easy loading of Markdown content by allowing users to attach an `input.md` file through a user-friendly file input element.
*   **Dynamic Rendering**: Automatically converts and displays the HTML output as soon as a Markdown file is successfully loaded.
*   **Syntax Highlighting**: Incorporates `highlight.js` to provide intelligent, automatic syntax highlighting for code blocks across a wide range of programming languages.
*   **Structured Output**: Renders the generated HTML content within a specific `#markdown-output` DOM element, ensuring a clean and organized presentation.
*   **Static Deployment**: The project is designed as a static web page, making it simple to deploy and host on any static hosting service.

## Setup Instructions

This project is a purely static web page and requires no complex build processes or server-side configurations.

1.  **Clone the Repository**:
    Begin by cloning the project repository to your local machine: