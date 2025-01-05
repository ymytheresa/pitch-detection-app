# TODO

## Windows-specific Setup

If you're running this project on Windows, replace the following scripts in `client/package.json`:

```json
"scripts": {
    "start": "set NODE_OPTIONS=--openssl-legacy-provider && npm run build:worker && react-scripts start",
    "build": "set NODE_OPTIONS=--openssl-legacy-provider && npm run build:worker && react-scripts build"
}
```

## Alternative Solutions

1. Downgrade Node.js to version 16.x
2. Upgrade react-scripts to version 5.0.0 or higher

## Future Improvements

- [ ] Make the build scripts work cross-platform automatically
- [ ] Update dependencies to remove legacy OpenSSL requirement
- [ ] Add cross-platform build documentation 


## update library
// ... existing code ...
pitch-detection = "0.3"
// ... existing code ...
