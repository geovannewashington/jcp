# jcp (javaScript creates password)

A client-side password generator built with JavaScript and bundled using Webpack.

The project focuses on generating configurable, random passwords directly in the browser, with all logic handled on the client side. It explores modular JavaScript structure, build tooling, and basic UI interaction without relying on external services.

Password generation logic is separated into reusable modules, while form handling and DOM interaction are kept isolated for clarity and maintainability. Assets are bundled with Webpack to produce a single optimized output for the browser.

The interface is intentionally simple and lightweight, with styling handled via plain CSS.

The application is available online at:
https://jcp-nu.vercel.app/

## Running locally

Clone the repository and install dependencies:

```bash
git clone https://github.com/geovannewashington/password-generator.git
cd password-generator
npm install
```

Build the project:
```bash
npm run build
```

Then open `public/index.html` in a modern browser.

## Notes

This project servers as a small example of client-side tooling, modulear JavaScript, and basic build 
configuration using Webpack.
