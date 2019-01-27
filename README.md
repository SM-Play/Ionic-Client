# Ionic-Client
Hybrid app using ionic3

## Getting Started

```
gimhyeon-uui-MacBook-Pro:Ionic-Client stories2$ ionic
   _             _
  (_) ___  _ __ (_) ___
  | |/ _ \| '_ \| |/ __|
  | | (_) | | | | | (__
  |_|\___/|_| |_|_|\___|  CLI PRO 3.20.1


  Usage:

    $ ionic <command> [<args>] [--help] [--verbose] [--quiet] [--no-interactive] [--confirm] [options]


  Global Commands:

    config <subcommand> ...... Manage CLI and project config values (subcommands: get, set)
    docs ..................... Open the Ionic documentation website
    info ..................... Print system/environment info
    login .................... Login with your Ionic ID
    signup ................... Create an Ionic account
    ssh <subcommand> ......... Commands for configuring SSH keys (subcommands: add, delete, generate, list, setup, use)
    start .................... Create a new project
    telemetry ................ (deprecated) Opt in and out of telemetry

  Project Commands:

    You are not in a project directory.

gimhyeon-uui-MacBook-Pro:Ionic-Client stories2$ ionic start SmartMirror blank
✔ Creating directory ./SmartMirror - done!
✔ Downloading and extracting blank starter - done!

? Would you like to integrate your new app with Cordova to target native iOS and Android? Yes
✔ Personalizing ionic.config.json and package.json - done!
> ionic integrations enable cordova --quiet
[ERROR] Error with ./SmartMirror/node_modules/ionic-angular/package.json file: FILE_NOT_FOUND
[ERROR] Error with ./SmartMirror/node_modules/@ionic/app-scripts/package.json file: FILE_NOT_FOUND
✔ Downloading integration cordova - done!
✔ Copying integrations files to project - done!
[OK] Added cordova integration!

Installing dependencies may take several minutes.

  ✨   IONIC  DEVAPP  ✨

 Speed up development with the Ionic DevApp, our fast, on-device testing mobile app

  -  🔑   Test on iOS and Android without Native SDKs
  -  🚀   LiveReload for instant style and JS updates

 ️-->    Install DevApp: https://bit.ly/ionic-dev-app    <--

> npm i
✔ Running command - done!
> git init

  🔥   IONIC  PRO  🔥

 Supercharge your Ionic development with the Ionic Pro SDK

  -  ⚠️   Track runtime errors in real-time, back to your original TypeScript
  -  📲   Push remote updates and skip the app store queue

Learn more about Ionic Pro: https://ionicframework.com/products

? Install the free Ionic Pro SDK and connect your app? Yes

-----------------------------------

> npm i --save -E @ionic/pro
✔ Running command - done!
> ionic link
✔ Looking up your apps - done!

? Which app would you like to link Nevermind
Not linking app.
> git add -A
> git commit -m "Initial commit" --no-gpg-sign

Next Steps:
* Go to your newly created project: cd ./SmartMirror
* Get Ionic DevApp for easy device testing: https://bit.ly/ionic-dev-app
* Finish setting up Ionic Pro Error Monitoring: https://ionicframework.com/docs/pro/monitoring/#getting-started
* Finally, push your code to Ionic Pro to perform real-time updates, and more: git push ionic master

gimhyeon-uui-MacBook-Pro:Ionic-Client stories2$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        SmartMirror/

no changes added to commit (use "git add" and/or "git commit -a")
gimhyeon-uui-MacBook-Pro:Ionic-Client stories2$ git add SmartMirror/*
The following paths are ignored by one of your .gitignore files:
SmartMirror/node_modules
Use -f if you really want to add them.
gimhyeon-uui-MacBook-Pro:Ionic-Client stories2$
```

### Install List

- npm: `3.10.10`
- node: `v6.11.5`
- Ionic: `3.20.1`


_Command_

```
npm install typescript -g
npm install -g ionic@3.20.1 cordova
```

## Running the tests

_Command_

```
cd <PROJECT-NAME>
ionic serve --lab
```


### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Check Ionic deploy project structure

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details