# A-Frame Webpack Boilerplate

> Simple Webpack configuration for your next a-frame project. You can use two different build processes. Development and production.

## Development Build

If you type npm start in the console the development config is run. The main.js file is automatically injected into the header and a new browser tab opens with hot module replacement.

```
npm start
```

## Production Build

The production command creates a dist folder for you. Including a minified file and hashed filename. Also the index.html is minified, comments and whitespace removed.

```
npm run build
```
