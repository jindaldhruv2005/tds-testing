# Hello World Web Page

## Overview
A minimal, static web page that displays the text “Hello World” and shows the bundled image file `sample.jpg` on the home page. The layout is responsive and works on both desktop and mobile devices.

## Setup
1. Ensure the following files are in the same directory:
   - index.html
   - sample.jpg (provided in this project)

2. No build tools are required. This is a plain HTML/CSS app.

3. Optional: To serve via a local static server (recommended for testing CORS and correct paths), you can use any of the following:
   - Python 3: python3 -m http.server 8000
   - Node (http-server): npx http-server -p 8000
   - Ruby: ruby -run -e httpd . -p 8000

## Usage
- Open index.html directly in your browser, or visit http://localhost:8000 (if serving locally).
- You should see the “Hello World” heading and the image from sample.jpg displayed below it.
- Make sure sample.jpg remains in the same folder as index.html so the image loads correctly.

## License
MIT License

Copyright (c) 2025 The Project Authors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the “Software”), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.