Class 1B - Digging deeper into Modern JS

MODERN JAVASCRIPT

Because JS is an old language, there is a lot of legacy syntax around, and it's helpful to know what's supported on the target platform.

These Modern JavaScript (ES6-ES9) features are essential to understand to code React (Native)

* let / const
* for ... in / for ... of
* class / extends 
* arrow functions
* async/await promises  
* destructuring objects {prop1,prop2}
* ...obj spread
* import vs require
JavaScript Classes and Object-oriented programming

Classes and class extensions example
JavaScript Classes on MDN
Class extensions on MDN
Arrow functions vs bind in React event listener

Minimal React button example
Context, binding and arrow functions explained
Event propagation (bubbling) explained
async/await

Loading data from API with async method
async/await overview
destructuring and spreading (...obj)

example of destructuring and spreading
Sharing code between files - require (CommonJS) vs import (ES6)?

NodeJS (<v13) uses CommonJS, ie.

require & import example
File1.js
module.exports = {dada:'dada'};

File2.js
const doda = require('./File1');
console.log(doda.dada);
React is using mainly ES6 import syntax

File3.js
export default {dada:'dada'};

File4.js
import doda from './File3';
console.log(doda.dada);
but require is still used in RN, expecially when including files and images. Also, if you need to share components with a NodeJS backend that doesn't support ES6 imports, you may need to rewrite them as CommonJS.

###Resources
string methods
loops

Assignment

fork a version of this sandbox
Load 10 random words from "https://random-word-api.herokuapp.com/word?number=10" using async fetch call
Find the longest word
Reverse the order of the letters in the longest word and output the result, eg. if the longest word is complexity the correct result should be ytixelpmoc
Use at least 3 features of ES6 we have covered today
Post your solutions as a github issue on this thread