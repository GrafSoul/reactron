# Reactron

React.js + Electron.js template for application development

![alt text](/design/screen.png 'Reactron')

## Run for start development version

```
git clone https://github.com/GrafSoul/reactron.git
cd reactron
npm install
npm start
// or
yarn install
yarn start
```

## Run for build a pre-release production app.

```
npm build
// or
yarn build
```

## Get ready files for installation on Windows

```
npm release
// or
yarn release
```

## Installed components

### React Router, Redux, Redux Thunk, React Bootstrap and other Dependencies

```
"dependencies": {
    "electron-is-dev": "^1.0.1",
    "electron-log": "^2.2.17",
    "electron-updater": "^4.0.6",
    "electron-devtools-installer": "^2.2.4",
    "node-notifier": "^5.3.0",
    "react": "^16.7.0",
    "react-dom": "^16.7.0",
    "react-redux": "^6.0.0",
    "react-router-dom": "^4.3.1",
    "react-scripts": "2.1.3",
    "reactstrap": "^7.0.2",
    "redux": "^4.0.1",
    "redux-thunk": "^2.3.0"
  }
```

### Develop Dependencies

```
"devDependencies": {
    "concurrently": "^4.1.0",
    "cross-env": "^5.2.0",
    "electron": "^4.0.1",
    "electron-builder": "^20.38.4",
    "electron-debug": "^2.0.0",
    "prettier": "^1.15.3",
    "wait-on": "^3.2.0"
  }
```

### Create Icons Pack

```
https://github.com/jaretburkett/electron-icon-maker

npm install -g electron-icon-maker
electron-icon-maker --input=file-name.png --output=./assets
```

Made on the basis of repositories:  
[fkhadra/cra-electron],  
[kodeflex/electron-cra],  
[kitze/react-electron-example]  
Thank you for the work done!

&#169; 2020 | Reactron | GrafSoul | [MIT licensed].

[mit licensed]: https://github.com/GrafSoul/reactron/blob/master/LICENSE
[fkhadra/cra-electron]: https://github.com/fkhadra/cra-electron
[kodeflex/electron-cra]: https://github.com/kodeflex/electron-cra
[kitze/react-electron-example]: https://github.com/kitze/react-electron-example
