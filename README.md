![dogescript](https://raw.github.com/remixz/dogescript/master/doge.gif)

## dogescript [![NPM version](https://badge.fury.io/js/dogescript.png)](http://badge.fury.io/js/dogescript)

[![Join the chat at https://gitter.im/aaronaardvark/dogescript](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/aaronaardvark/dogescript?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

(aka when Zach went insane)

This is an implementation of the best new compile-to-JS language, dogescript. Wow. 

And yes, I am very aware I went about a very, er, *non-conventional*, way of parsing a language, and is probably riddled with bugs and edge-cases. However, this is dogescript, so anything goes!

```
    wow
         such dogescript
     very compiled
                  next-generation
       npm wow
```


### Installation

`npm install -g dogescript`

### Usage

#### Command Line

`dogescript` without a file launches a REPL.

`dogescript location/to/dogescript.djs` pipes the result to stdout. Use a command like `dogescript dogescript.djs > compiled.js` to save to a file.

Options:

* `--beautify` - Runs the code through a beautifier.
* `--true-doge` - Implements "true doge" mode, which splits lines by 3 spaces, instead of by newlines. This stays behind a flag until the spacing it exports is identical to non-true-doge mode.

#### Javascript

`dogescript(file, beauty, trueDoge)`
* `file` - A string of Dogescript.
* `beauty` - A boolean, set to true if you want the output to be ran through a beautifier.
* `trueDoge` - A boolean, set to true if you want to enable true-doge mode.

### Language documentation

* Introduction to Dogescript - http://alexdantas.net/stuff/posts/introduction-to-dogescript/
* `LANGUAGE.md`

### Projects using dogescript

- [Doge Adventure!](https://github.com/ngscheurich/doge-adventure): A text adventure game inspired by [leonsumbitches](http://dailydoge.tumblr.com/post/21839788086/leonsumbitches-you-have-encountered-a-doge).
- [dogeify](https://github.com/remixz/dogeify): A Browserify transform for dogescript.
- [grunt-dogescript](https://github.com/Bartvds/grunt-dogescript): A grunt plugin to compile dogescript.
- [Doge Game of Life](https://github.com/eerwitt/doge-game-of-life): Conway's Game of Life in dogescript.
