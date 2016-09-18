# Webpack Starter
Simple directory and config setup for a Webpack project with front-end web only. 

## Development 
### Install
```
npm install
```

### Serve

To serve at http://localhost:8080/:

```
npm start

//or 

webpack-dev-server --inline  --content-base public/ 
```

### Build

To compile HTML/CSS and JavaScript files for production:

```
webpack --config webpack.config.js
```

## Sublime 3

```
Ctrl + Shift + P
Package Control: Install package
'Babel'
```

At the bottom right of your sublime window, switch your build to 'babel (javascript)'.