# Hackaru Desktop

[![Build Status](https://travis-ci.org/ktmouk/hackaru-desktop.svg?branch=master)](https://travis-ci.org/ktmouk/hackaru-desktop)

[Hackaru](https://github.com/ktmouk/hackaru) for Desktop.

## Feature

- This app is created using [Electron](https://github.com/electron/electron). Support Windows, macOS and Linux.
- AutoTracking support.
- Track your computer status. (e.g., When your notebook will be suspend, stop the timer.)
- Completely open source.

## AutoTracking
You can time automatically you are using favorite Applications. (e.g., Sketch, Atom editor...)

<img src="./docs/images/auto-tracking.gif" width="730">

## Installation

1. Download zip and install.
  - **On Mac**
    1. Download hackaru-osx.zip from [Release](https://github.com/ktmouk/hackaru-desktop/releases).
    2. Extract zip file and execute Hackaru-x.y.z.dmg.
    3. Move Hackaru icon to Application folder.

  - **On Windows**
    1. Download hackaru-win.zip from [Release](https://github.com/ktmouk/hackaru-desktop/releases).
    2. Extract zip file and execute Hackaru-x.y.z.exe.

  - **On Linux**
     1. Download hackaru-linux.zip from [Release](https://github.com/ktmouk/hackaru-desktop/releases).
     2. Extract zip file and execute Hackaru-0.1.0.AppImage.

2. Launch installed application.

3. Enter [Hackaru API server](https://github.com/ktmouk/hackaru-api) URL and authenticate.  
   If you have an account in [hackaru.app](https://hackaru.app), URL is https://api.hackaru.app (default).  
   If you want to use your private server, Enter your API server URL (e.g., http://localhost:3000)


  <img src="./docs/images/login_screen.png" width="300">

## Contributors

1. [Fork it](https://github.com/ktmouk/hackaru-desktop/fork).

2. Clone a forked repository and create a new branch.
```
$ git checkout -b new-feature
```

3. Run this app in dev mode.
```
$ npm install
$ npm run dev
```
> This app is using [atom/node-keytar](https://github.com/atom/node-keytar) to store OAuth tokens.  
> So you may need to install libsecret if build on Linux. See [Detail](https://github.com/atom/node-keytar).

4. Improve codes.

5. Run ESLint.
```
$ npm run lint:fix
```

6. If it has no problem, Create a new Pull request!

## License

- [MIT](./LICENSE)

---

This project was generated with [electron-vue](https://github.com/SimulatedGREG/electron-vue) using [vue-cli](https://github.com/vuejs/vue-cli).
