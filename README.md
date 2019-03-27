# A-Frame Webpack Boilerplate

> Simple Webpack configuration for your next a-frame project. You can use two different build processes. Development and production.

## Setting everything up

You'll need [NodeJS](https://nodejs.org/en/). I used v11.4.0 for the development process. You can use [nvm](https://github.com/creationix/nvm) to easily install and manage different versions of node on your system.

```
node -v
# or
nvm current
```

If you have everything set up just `cd` into the directory and type `npm install` into the terminal

```
cd INTO_PROJECT_FOLDER
npm install
```

### Development Build

If you type npm start in the console the development config is run. The main.js file is automatically injected into the header and a new browser tab opens with hot module replacement.

```
npm start
```

### Production Build

The production command creates a dist folder for you. Including a minified file and hashed filename. Also the index.html is minified, comments and whitespace removed.

```
npm run build
```
