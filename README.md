# AsanGPT Interface

This project is a simple chat interface for interacting with the AsanGPT API. The interface allows users to input text, send it to the API, and receive a response. The chat messages are displayed with a typing effect, and code snippets within the messages are syntax-highlighted.

## Features

- **Chat Interface**: A user-friendly chat interface where users can type messages and view responses.
- **Typing Effect**: The bot's responses are displayed with a typing effect to simulate real-time typing.
- **Syntax Highlighting**: Code snippets within the messages are syntax-highlighted using the `highlight.js` library.
- **Markdown Parsing**: Messages are parsed as Markdown using the `marked` library.
- **Copy Button**: Code snippets have a copy button that allows users to easily copy the code to their clipboard.
- **Loader Indicator**: A loader indicator is displayed on the send button during API calls.

## Libraries Used

- [marked](https://github.com/markedjs/marked) for Markdown parsing.
- [highlight.js](https://github.com/highlightjs/highlight.js) for syntax highlighting.

## Setup and Usage

### Prerequisites

Ensure you have the following prerequisites installed:

- A web server to serve the HTML file.
- An API endpoint for AsanGPT (replace `http://localhost:1234/v1/chat/completions` with your actual API endpoint).

### HTML, CSS, and JavaScript Code

The main HTML file should include the necessary styles, HTML structure, and JavaScript code. Here is a brief overview of the main components:

- **HTML**: The HTML structure includes a container for the chat interface with sections for the header, chat messages, and input area.
- **CSS**: Styles for the chat interface, including the chat container, messages, input field, and loader indicator.
- **JavaScript**: The JavaScript code handles user input, API calls, message rendering, typing effect, and syntax highlighting.

### JavaScript Functions

Below are key JavaScript functions used in the project:

#### Initialize Libraries
```html
<script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/11.4.0/highlight.min.js"></script>
<script>
    hljs.highlightAll();
</script>
