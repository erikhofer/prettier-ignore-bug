# Prettier ignore bug

Reproduction:

    npm install
    npm start

The directory `src/ignored-dir` is listed in `.prettierignore`. Despite this, the contained file starting with α is checked by `prettier-check`.