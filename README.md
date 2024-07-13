<img align=center src="images/banner.png">

# Introduction
What is primebit? **primebit.js** is a npm package that gives users the ability, to log things in a clean way!


# Types
You can use up to 4 different log types, which are `log (default)`, `error`, `warning`, and `success`


# `⬇️` Installation

To install primebit You can do the following:

```js
npm install primebit.js
```

# `👀` Implentation

After you've installed primebit, you can add your text, and implement the logging types like this:

```js
const p = require("primebit.js")

p.log("Hello World!")
```

# `⚙️` Options
By default, the text doesnt have a color to it, to fill the color in, you can use the `options` property to fill the text color like this:

```js

const p = require("primebit.js");

p.log("Hello World!", {
  options: {
    filled: true
  }
});
```

And after that, your good to go!