# Seed project for React using webpack and express

Use this seed application to quickly bootstrap your prototypes. The setup is self made and has only really necessary dependencies installed.

This project includes:
- React 16.13.1 
- webpack 4.42.1
- express 4.17.1
- babel loader 8.1.0 and babel core 7.9.0
- livereload 0.9.1
- ESLint 6.8.0
- prettier 2.0.2

## Getting started

```bash
# build production bundle in /public
npm run build

# start express server
npm start

# build dev bundle and start dev server
npm run dev
```

## Linting and formatting
This project uses [prettier](https://github.com/prettier/prettier) for code formatting in conjunction with [ESLint](https://github.com/eslint/eslint) for code linting and fixing.

```bash
# lint
npm run lint
```

To enjoy automatic linting and formatting  the following configuration for [Visual Studio Code](https://github.com/microsoft/vscode) can be used.

*settings.json*
```json
{
    "editor.formatOnSave": false,
    "[json]": {
        "editor.formatOnSave": true,
    },
    "[less]": {
        "editor.formatOnSave": true,
    },
    "[javascript]": {
        "editor.formatOnSave": false,
    },
    "editor.codeActionsOnSave": {
        "source.fixAll.eslint": true,
        "source.fixAll.stylelint": true,
        "source.fixAll.tslint": true
    },
    "eslint.validate": ["javascriptreact"],
    "javascript.format.enable": false,
    "javascript.validate.enable": false,
}

```

## Todos
- Setup tests with mocha and enzyme
