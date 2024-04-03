## Introduction To JavaScript 🧑‍💻
- What is JavaScript❓
- History Of JavaScript❓✍
- JavaScript Versions❓
- How to Run JavaScript❓


### Introduction:
- JavaScript is a powerful, versatile programming language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. While initially created to make web pages alive, its scope has grown far beyond that.

>##### { In Hindi }
> `JavaScript ek programming language hai jo web pages ko interactive aur dynamic banane ke liye use hoti hai. Iska use web development ke alawa bhi hota hai, jaise ki mobile apps, game development, aur server-side programming me.`

### JavaScript:
- JavaScript is a high-level, interpreted scripting language that is characterized by its dynamism, weak typing, first-class functions, and prototype-based object-orientation. it is most well-known as the scripting language for Web pages, but it's also used in many non-browser environments such as Node.js, Apache CouchDB,and Adobe Acrobat. JavaScript enables interactive web pages and is an essential par of web applications.

>##### { In Hindi }
> `JavaScript ek script language hai jo web browser me run hoti hai aur web pages ko user ke interaction ke according time update kar sakti hai. Isse aap webpage me animations, checking forms, loading new images, aur data submit karte time page ko refresh kiye bina hi new information show kar sakte hain.`


### History Of JavaScript: 
- JavaScript was created in `1995` by `Brendan Eich` while he was an engineer at Netscape. initially developed under the name Mocha, then renamed to `LiveScript`, and finally to JavaScript, reflecting Netscape's support of Java within its browser. the language was designed to complement Java and to appeal to non-programming language, sharing only superficial similarities.

     Netscape submitted JavaScript to Ecma international, leading to the standardization of the language in the form of `ECMAScript`, which continues to evolve. This standardization process ensures that JavaScript behaves predictably across different platforms.

>##### { In Hindi }
> `1995 me Brendan Eich ne Netscape company ke liye JavaScript banayi thi. Shuru me iska naam Mocha tha, phir LiveScript aur finally JavaScript rakh diya gaya. JavaScript ko Java ke lightweight companion ke roop me develop kiya gaya tha, lekin ab ye dono alag-alag languages hain.`


## JavaScript Versions:
JavaScript versions are often referred to in terms of their `ECMAScript (ES)` standards:

***ES1(1997):*** The first edition.

***ES2(1998):*** Introduced function overloading, and added a new type called `"Boolean"`.

***ES3(1999):*** Added `Regular Expressions`, better string handling, new control statements, `try/catch`. 

***ES4:*** Abandoned in favor of ES3.1.

***ES5(2009):*** Added `"strict mode"` `JSON support`, and more. `String.trim()` `Array.isArray()` `Array iteration methods` `trailing commas for object literals` It's widely supported in browsers.

***ES6	ECMAScript (2015):*** A significant update that introduced `classes`, `modules`, `arrow functions`, `promises`, and more. This update brought JavaScript much closer to other class-based languages, making it easier to use for large-scale applications.

Added  `let` and `const` `default parameter values` `Array.find()` `Array.findIndex()`

***Subsequent versions (ES2016+, annually released):*** These have introduced additional features like `async functions (ES2017)`, `rest/spread properties (2018)`, optional chaining, and `nullish coalescing (2020)`

***ES(2016):*** Added `exponential operator (**)` and `Array.includes()`.

***ES(2017):***  Added `string padding`, `Object.entries()`, `Object.values()`, `async functions`, `shared memory`
Allows `trailing commas` for function parameters.

***ES(2018):*** Added `rest / spread properties`,  `asynchronous iteration`, `Promise.finally()`
Additions to `RegExp`

***ES(2019):*** `String.trimStart()`, `String.trimEnd()`, `Array.flat()`, `Object.fromEntries`
Optional `catch binding`.

***ES(2020):*** The Nullish Coalescing Operator (??)

>***ES6:***  `Modularization` `Arrow function` `Function parameter defaults` `Template string` `Destructuring assignment` `Extension operator` `Object attribute shorthand` `Promise` `Let` and `Const` and `hoisting`.

>***ES7:***  `Exponentiation operator (**)` `includes()`

>***ES8:***  `String padding: padStart() && padEnd()` `Trailing commas` `async/await` `ShareArrayBuffer` and `Atomics objects` Method for accessing to objects such as `Object.values()`, `Object.entries()`,`Object.keys()`,`Object.getOwnPropertyDescriptors()`… 

>***ES9:*** `asynchronous iterator`
`Template string` for `non-escape` sequence 
`Regular expression reverse (look behind) assertion (this article)`
`Regular expression (Unicode escape)`
`Regular expressions/dotAll mode`
`Regular expression named capture group`
`Object expansion operator`
`Promise.finally()`

>***ES10:*** `flat() method` and `flatMap() method`, `trimStart() method` and `trimEnd() method`, function `Object.fromEntries()`, `Symbol.description()`, `String.matchAll()`, `Function.prototype.toString()`, Simplify `try {}` `catch {}` and modify the `catch binding`, New basic data type `BigInt`.

>***ES11:*** `BigInt()`, `Dynamic Import`, `Optional chaining operator`, `Promise.allSettled()`, `globalThis`, `matchAll()`.

>***ES12:*** `String.replaceAll()`, `Promise.any()`, `WeakRef()`,  `Numeric-separator` `Logical Assignment Operators`.

## How to Run JavaScript![?](image.png)

- **In a web Browser:** Javascript code can be written directly within HTML documents and executed by the web browser. To run JavaScript in a web browser, you can simply include it between `<script>` tags:

>##### { In Hindi }
>**Web Browser me:** HTML document me `<script>`tag ke andar direct JavaScript code likh sakte hain. Browser automatically ise run karega.

```bash
<!DOCTYPE html>
<html>
<body>
    <script>
        alert('Hello, Duniya!');
    </script>
</body>
</html>
```

- **Using Node.js:** For server-side JavaScript or running JS outside of a browser, you can use `Node.js`. First, install `Node.js` from [nodejs.org](https://nodejs.org/en) Then, write your JavaScript code in a .js file and run it using the Node.js interpreter from the command line:

>##### { In Hindi }
>**Node.js ke Saath:** Agar aapko browser ke bahar JavaScript run karni hai, toh `Node.js` use kar sakte hain. `Node.js` install karein, phir `.js` file me code likh kar command line se `node filename.js` command ke sath run karein.

```bash
// example.js
console.log('Hello, Duniya!');
```
Command line me:
```
node example.js
```

-----









