# E-commerce Website

An early Node.js web application foundation with an Express server, EJS templates and a MongoDB connection.

## Current implementation

- `app.js` configures Express middleware and serves static files from `public/`.
- EJS templates are loaded from `views/`.
- The `/` route renders `pages/index`.
- Mongoose connects using the `MONGODB_URI` environment variable.
- The server reads `PORT`, defaulting to `3000`.

## Development

Install the dependencies listed in `package.json`, configure a development MongoDB connection outside version control and run `node app.js`.

## Status

This repository is an application foundation. A complete shopping cart, checkout, payment integration, authentication flow or automated test suite is not established by the current entry point.

[Web development collection](https://github.com/aminzoroufi/aminzoroufi/blob/main/projects/web-development.md)
