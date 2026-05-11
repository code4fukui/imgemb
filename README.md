# imgemb

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, client-side tool to convert image files into Base64-encoded data URLs, ready for embedding in HTML `<img>` tags. This allows you to include images directly in your source code without needing separate files.

## Demo

**[Try it live](https://code4fukui.github.io/imgemb/)**

The interface consists of a dashed drop zone for your image file and a textarea that displays the resulting HTML tag.

## Features

-   **Drag-and-Drop Interface:** Simply drag an image file into the browser.
-   **Instant Conversion:** Generates a Base64-encoded `data:` URL on the fly.
-   **HTML Tag Output:** Automatically wraps the result in a complete `<img src="...">` tag.
-   **Purely Client-Side:** All processing happens in your browser. Your images are never uploaded to a server.
-   **Self-Contained:** The entire tool is a single, portable HTML file.

## Usage

1.  Open the [demo page](https://code4fukui.github.io/imgemb/).
2.  Drag an image file from your computer and drop it onto the dashed area.
3.  The complete `<img src="...">` tag will appear in the textarea below.
4.  Copy the generated HTML and paste it into your project.

## Requirements

A modern web browser that supports the `FileReader` API (e.g., Chrome, Firefox, Safari, Edge).

## License

[LICENSE](LICENSE)