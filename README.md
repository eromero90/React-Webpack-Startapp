#React-Webpack-Startapp

### Quick start
**Make sure you have Node version >= 4.4.2 and NPM >= 3**

# install the repo with npm
npm install

## Running the app
After you have installed all dependencies you can now run the app. Run `npm start` to start a local server using `webpack-dev-server` which will watch, build (in-memory), and reload for you. The port will be displayed to you as `http://localhost:8080/`.


## Other commands

### build production dist
```bash
npm run build
```

### run tests
```bash
npm test
```

## Setting proxies
If you need to set the NPM proxy:
```bash
npm config set proxy http://{host}:{port}
npm config set https-proxy https://{host}:{port}
```