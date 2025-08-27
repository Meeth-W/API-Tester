# Frontend Framework for Backend Testing

## Overview

This project is a frontend framework designed to test any backend API. It provides a user-friendly interface for sending requests and viewing responses, making backend testing faster and more efficient.

## Features

- **API URL Input:** Enter the endpoint you want to test.
- **JSON Data Input:** Write or paste JSON payloads with syntax highlighting for better readability.
- **Flexible Data Input:** Add any other data types required for your API requests.
- **Send Button:** Trigger the API call and view the response instantly.

## Built With

- [React.js](https://react.dev/) – JavaScript library for building user interfaces.
- [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework for styling.

## External Libraries

- [`react-syntax-highlighter`](https://github.com/react-syntax-highlighter/react-syntax-highlighter)  
    _For JSON input with syntax highlighting. Install with:_  
    ```bash
    npm install react-syntax-highlighter
    ```
- [`prismjs`](https://prismjs.com/)  
    _Required by react-syntax-highlighter for syntax highlighting. Install with:_  
    ```bash
    npm install prismjs
    ```
- [`axios`](https://axios-http.com/)  
    _For making HTTP requests. Install with:_  
    ```bash
    npm install axios
    ```

## Getting Started

1. **Clone the repository**
2. **Install dependencies**
     ```bash
     npm install
     ```
3. **Start the development server**
     ```bash
     npm start
     ```

## Usage

1. Enter the API URL you want to test.
2. Input your JSON data or any other required data.
3. Click the **Send** button to make the request.
4. View the API response directly on the page.

## License

This project is open source and available under the [MIT License](LICENSE).