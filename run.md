# run

* Install node and yarn first time.

```
brew install node@18 yarn
```

* Run `yarn install`, to install all required packages.
* Run `yarn start`, to run the application.
* To make [package](https://www.electronjs.org/docs/latest/tutorial/quick-start#package-and-distribute-your-application)
```
yarn add --dev @electron-forge/cli
npx electron-forge import
yarn make

```
* To run the app
```
open ./out/quick-start-electronjs-darwin-x64/quick-start-electronjs.app
```
