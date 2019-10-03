# js-student-boilerplate

This boilerplate is a great starting point to expedite and assist students who are learning front-end development, namely 'imperative style' JavaScript. It includes starter files, linting and VS Code settings and extensions.

The following directions assume that you have either manually 'forked' this repo to your own GitHub account, or that that has been done for you via GitHub Classroom, or some other way. It's also assumed that you have NodeJS installed and that you will be using VS Code (*not* Visual Studio).

1. `git clone` this repo.
  a. Click the green button on the GitHub page.
  b. Choose 'Use HTTPS' if it's not already selected.
  c. Click the 📋icon. This copies the URL for this repository.
  d. Jump into your terminal and change to whatever directory you want to use to store this repo. If unsure, do the following: `cd ~` (go back to your home directory). `cd Code` to change to that directory, or if it doesn't exist, `mkdir Code` first to create it.
  e. Finally, to 'copy' the repo onto your local machine into, for example, your 'Code' directory, do: `git clone` and paste in the URL from your 📋.
  f. `cd js-student-boilerplate` (assuming that you didn't specify a different folder when you `clone`d). Depending on your terminal settings, you will probably see something about 'master' indicating that you are in a `git` repository. 👏🏾
2. `npm install`. This pulls in NodeJS packages that will provide some useful tooling to help us as we code. It will pull in packages that have been specified inside a special 'manifest' file in this directory called 'package.json'.
3. `code .` This should fire up VS Code and start you off in your current directory.
4. Watch in the bottom right of your screen. If it prompts you to install some extensions, do it!

😎Your coding environment should be ready to rumble. 🤓

P.S. The settings for VS Code are set to use ['Incosolata' font](https://fonts.google.com/specimen/Inconsolata?selection.family=Inconsolatad).

## Live-Server

`npx live-server .` should fire up a 'hot reloading' [live server.](https://www.npmjs.com/package/live-server)
