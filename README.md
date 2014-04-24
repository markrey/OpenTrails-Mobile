Trails Mobile
=============

Trails Mobile is a multi-device application that allows users of trails to cache trail information offline.

## Installation

***Note: the following requires that nodejs is installed, follow the [node installation instructions](https://github.com/joyent/node/wiki/Installing-Node.js-via-package-manager) for your system if needed.***

In order to test this application, you'll first need to install Cordova. Do so with the following commands: 

```
sudo npm install -g cordova
sudo npm install -g ios-sim
```

Once you have Cordova installed, clone the GitHub repo. **In the following command, change `YOUR_PROJECTS_DIRECTORY` to the directory you want the project to be downloaded into**:

```
git clone https://github.com/rclosner/trails-mobile ~/YOUR_PROJECTS_DIRECTORY/trails-mobile
```

Now navigate to the directory with:

```
cd ~/YOUR_PROJECTS_DIRECTORY/trails-mobile
```

To build and launch the application from the source code and view it in the iOS emulator, use:

```
cordova build ios
cordova emulate ios
```

## Usage

TODO: Fill me in

## Contribution

  * Fork the project.
  * Make your feature addition or bug fix.
  * Commit, do not mess with Rakefile or version
  * Send me a pull request. Bonus points for topic branches.
