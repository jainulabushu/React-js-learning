# React-js-learning
video course by Mosh Hamedani
 
 learning 
 * master react fundamentals
 * Build Reusable Components
 * Render Data
 * Handle Events
 * Debug Your React Apps
 
 React is a javascript library for building user interfaces
 
 Angular is a framework
 React is a library
 
need to download and install nodejs https://nodejs.org/en/

open command prompt on windows in start window search

npm i -g create-react-app@1.5.2

open extension pannel in vs code

in vs code search for simple react snippets and install it by Burke Holland

in vs code search and install Prettier - Code formatter by esbenp Prettier

in vs code> settings> user> formatting> formate on save> tick it

on comand prompt >type> create-react-apps react-app >run it >shift + fn + f10 or enter

its going to install 
*development server 
*Webpack
*Babel
*and bunch of other tools

npm is the default package manager for the JavaScript runtime environment Node.js.

finally run>cd react-apps
npm start


this will open port on chrome page as http://localhost:3000/

drag and drop react-apps folder to vs code editor to open

chrome> babeljs.io/repl

babel> here we can type modern javascript code> babel convert that code into that browsers can understand

const element = <h1>Hello World</h1>;

babel convert jsx code to react js code

delete all files form src (source) and create new index.js file under src file in vs code

type the below code in vs code and save it, then check browser it will open a blanck tab named http://localhost:3000/

then open console by clicking ctrl+shift+i

import React from 'react';  //React = object, 'react' = module, same applicable for all imports
import ReactDom from 'react-dom';

const element = <h1>Hello World</h1>;  //jsx expression
ReactDom.render(element, document.getElementById('root'));

o/p: display hello world in chrome page












