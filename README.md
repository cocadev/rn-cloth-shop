React-Native Cloth APP 2



## Requirements

### Mandatory

- MacOS.
- [Xcode](https://itunes.apple.com/br/app/xcode/id497799835?mt=12) and [Android Studio](https://developer.android.com/studio/index.html).
- [Homebrew](https://brew.sh/).
- [Node](https://nodejs.org), [Watchman](https://facebook.github.io/watchman/) and [React Native](https://facebook.github.io/react-native/).

### Optional

- [Atom](https://atom.io/), [Linter](https://atom.io/packages/linter) and [ESLinter](https://atom.io/packages/linter-eslint).
- [Oh My ZSH!](http://ohmyz.sh/) (add the line `source ~/.bash_profile` to **~/.zshrc** file).


## Enviroment Settings

### Mandatory

- Install [Xcode](https://itunes.apple.com/br/app/xcode/id497799835?mt=12) and run `xcode-select --install` on [Terminal](ssh://).

- Install [Android Studio](https://developer.android.com/studio/index.html) and create an emulator.

- Install [Homebrew](https://brew.sh/).

- Install [Node](https://nodejs.org), [Watchman](https://facebook.github.io/watchman/) and [React Native](https://facebook.github.io/react-native/):

```
brew update
brew install node
brew install watchman
npm install -g react-native-cli
```

### Optional

- Install [Atom](https://atom.io/) and follow packages: `lint`, `lint-eslint` and `linter-ui-default`.


## Steps to Run

### 1. Clone project and install the dependencies

```
git clone git@github.com:Bruno-Furtado/fastbuy-app.git && cd fastbuy-app && bundle install
```

### 2. Open the project in Android Studio

```
open -a /Applications/Android\ Studio.app android
```
> Press 'OK' on first alert, and do not update gradle plugin on second.

### 3. Start the server

```
react-native start
```

### 4. Make sure you have a simulator installed and run the app on iOS

```
react-native run-ios
react-native run-ios --simulator "My Simulator (12.1)"
```

### 5. Make sure you have started an emulator and run the app on Android

```
react-native run-android
```

## Architecture

<p align="center">
  <img src="https://fastbuy-fd9d7.firebaseapp.com/images/arch.png" alt="FastBuy Architecture" title="FastBuy Architecture">
</p>

## Todolist

- [x] Sign Up and Authentication
- [x] Create a Product
- [x] Product List
- [x] Delete a Product
- [x] Edit a Product
- [x] Camera
- [x] Redux framework
- [x] Firebase Integration (Analytics, Auth, Database, Crashlytics and Performance)
- [x] Translation (with [react-native-languages](https://github.com/react-community/react-native-languages))

