TODO: Proof and Build
# Getting Started with React

To get stared with React, we'll use Create React App. Starting out with Create React App allows us to get started locally with React without having to set up build configurations. Create React App works on macOS, Windows, and Linux. We just need to have Node.js installed.

If something doesn’t work, please contact your instructor immediately.

### Get in a directory

Go inside of your projects directory or create a new directory that is not already inside of a git repository. You could call this React-Library. We called ours JavaScript-301-ReactLibrary, but you can just call yours ReactLibrary.

```sh
mkdir ReactLibrary
cd ReactLibrary
```

At this phase go ahead and set up a remote repository with a README.md file. Go ahead and push your README.md file to the remote.


### Install an instance of Create React App

Open up the starter app inside of VS Code and open the terminal. We'll now go through the following steps to create your initial app, using Facebook's Create React App starter. Note that the npx command is [correct](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b). 

```sh
ReactLibrary> npx create-react-app react-fundamentals
ReactLibrary> cd react-fundamentals
```

### Run Create React App

After the app finishes loading, you can run the app locally by using the following command:

```sh
npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser. You should see the starter app:
![Initial Run](../assets/1-cra-initial.PNG)


Here's Facebook's starter screenshot for more help. Note that they use the generic name `my-app` for their app:
<p align='center'>
<img src='https://cdn.rawgit.com/facebookincubator/create-react-app/27b42ac/screencast.svg' width='600' alt='npm start'>
</p>


### App Orientation
After creating the application in your terminal, do the following: 
1. Open up the react-fundamentals folder that contains the app.
2. Take a look at the files in the src folder and get an idea of where things are located. By no means do you have to know what is happening right now. Know that for the most part, we'll be working in the src folder. <br />

### Create Directories
As you open the app, you have a few simple set up tasks:

Please right click on the <b>src</b> folder and add 4 folders: 'assets', 'components', 'constants', and 'styles'. 

The project will then have the following structure:

```
react-library
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   └── favicon.ico
│   └── index.html
│   └── manifest.json
└── src
    └── assets
    └── components
    └── constants
    └── styles
    └── App.css
    └── App.js
    └── App.test.js
    └── index.css
    └── index.js
    └── logo.svg
    └── registerServiceWorker.js
```


### SCSS Setup
Next, we'll get started on setting up SCSS. 

[2 - SCSS-Setup](2-Sass-Setup.md)







