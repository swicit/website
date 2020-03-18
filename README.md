# SWIC IT Club Website

## About

This repo includes opinionated settings and VS Code extensions. Both [ESLint](eslint.org) and [Stylelint](stylelint.io.)

## Getting Started

1. `git clone` this repo.
   a. Click the green button on the GitHub page.
   b. Choose 'Use HTTPS' if it's not already selected.
   c. Click the 📋icon. This copies the URL for this repository.
   d. Jump into your terminal and change to whatever directory you want to use to store this repo. If unsure, do the following: `cd ~` (go back to your home directory). `cd Code` to change to that directory, or if it doesn't exist, `mkdir Code` first to create it.
   e. 'copy' the repo onto your local machine into, for example, your 'Code' directory, do: `git clone` and paste in the URL from your 📋.
   f. `cd` into the `clone`d diretory.
2. `npm install`. This pulls in NodeJS packages that will provide some useful tooling to help us as we code. It will pull in packages that have been specified inside a special 'manifest' file in this directory called 'package.json'.
3. `code .` This should fire up VS Code and start you off in your current directory.
4. Watch in the bottom right of your screen. If it prompts you to install some extensions, do it!

P.S. The settings for VS Code are set to use ['Incosolata' font](https://fonts.google.com/specimen/Inconsolata?selection.family=Inconsolatad).

## BrowserSync

`npm run serve` should fire up a 'hot reloading' [BrowserSync](https://browsersync.io/) server.
