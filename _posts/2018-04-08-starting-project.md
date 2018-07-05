---
layout: post
title: Starting a React project
categories: dev
tags: dev js node react
---

I have started working on my side/pet project. As it is with these kind of projects (at least for
me) - the hardest part is to start. My guess, the main reason for that is the setup. We tend to overwhelm ourselves with _EVERYTHING_ we want to do.

Side project is like that proud bird - it won't fly if you don't kick if off the ground.

Things that we need to decide before we start - tech stack. I will use React and Redux.

- git
- npm
- gulp / webpack
- eslint (airbnb + own rules)
- ES6+ (Babel)
- Sass
- React 16
- Redux (Redux-Saga maybe)
- enzyme | ava
- something for "styleguide" (uizoo or storybook maybe)
- something else I have missed

Start with getting some kind of git repo provider (github / gitlab / bitbucket) and setup ssh so
you don't need to enter password every time. Search for how to install git on your machine.
Also npm (or yarn - whatever floats). Initialize the project with

[`npm init`](https://docs.npmjs.com/cli/init)

Add webpack (and/or gulp) and babel to the project, then add eslint and airbnb rules (or any
other you like) and make sure to install all the plugins that you want to use.

`npm install --save-dev webpack babel-core babel-loader babel-preset-react @babel/preset-env`
`npm install --save-dev eslint eslint-config-airbnb`

Install React, ReactDOM and PropTypes.

`npm install --save react react-dom prop-types`

Structure of the project can be whatever you like, don't be picky, just search for
`<tech> project folder structure` and pick something from the first few results. If you get stuck
here - you will fail. Choose. Any. I does not matter.
