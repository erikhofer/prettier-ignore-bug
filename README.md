# Prettier ignore bug

Reproduction:

    npm install
    npm start

The directory `ignored-dir` is listed in `.prettierignore`. Despite this, the file starting with α is checked by `prettier-check`.