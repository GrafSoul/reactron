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
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "electron-devtools-installer": "^3.2.0",
    "electron-is-dev": "^2.0.0",
    "electron-log": "^4.4.8",
    "electron-updater": "^5.3.0",
    "node-notifier": "^10.0.1",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-redux": "^8.0.5",
    "react-router-dom": "^6.10.0",
    "react-scripts": "^5.0.1",
    "reactstrap": "^9.1.8",
    "redux": "^4.2.1",
    "redux-thunk": "^2.4.2",
    "web-vitals": "^2.1.4"
  },
```

### Develop Dependencies

```
  "devDependencies": {
    "concurrently": "^8.0.1",
    "cross-env": "^7.0.3",
    "electron": "^24.0.0",
    "electron-builder": "^23.6.0",
    "electron-debug": "^3.2.0",
    "prettier": "^2.8.7",
    "wait-on": "^7.0.1"
  },
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

&#169; 2023 | Reactron | GrafSoul | [MIT licensed].

[mit licensed]: https://github.com/GrafSoul/reactron/blob/master/LICENSE
[fkhadra/cra-electron]: https://github.com/fkhadra/cra-electron
[kodeflex/electron-cra]: https://github.com/kodeflex/electron-cra
[kitze/react-electron-example]: https://github.com/kitze/react-electron-example
