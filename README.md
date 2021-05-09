# snd-testing-tool

Developed for checking consistency of flow tables, backtraces of network traffic, checking switch forwarding rules, recording and replaying of all or selected traffic, and detection of network configuration changes using Node.js and Python.


## Desktop app

`Node.js` is required so use `brew install node` to install it!

### For developing
In the `desktop` folder

At the first time, install all dependencies packages needed for Codeship
```sh
npm install
```

Run the app
```sh
npm start
```
### Builds the app (binary file)
In the `desktop` folder

For OS X app

```sh
npm run build-osx
```

For Linux app

```sh
npm run build-linux
```
