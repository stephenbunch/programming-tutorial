# Programming Tutorial
Welcome to my programming tutorial. My goal is to teach you **how to think**, not what to think.

There's a lot of material here, so get a cup of coffee and absorb this tutorial at your own pace.

I use "levels" instead of chapters to emphasize order. Concepts build on each other, so it's important that you don't jump around too much.

At the end of each section, I include some questions and/or sample coding problems to verify that you understood the section correctly. **You must do these.** It's the only way to know that you're on the right track.

Also:
* Try to finish one level each week and spread things out so your mind has time to process. I usually have to sleep on a new concept before I'm able to wrap my head around it.
* Don't take too many breaks. You'll forget things and it'll be difficult to keep going.
* It's just like learning an instrument. [Practice makes perfect.](http://lifehacker.com/5939374/a-better-way-to-practice)
* Be resourceful. Search for YouTube videos if you have to. I've discovered that it's easier for me to learn a new concept if I can find a video tutorial that explains it.
* Be curious. The best programmers are super curious about **how and why things work**.


## Table of Contents
* [Level 1](#level-1)
  * [What is code?](#what-is-code)
  * Values
  * Variables
* Level 2
  * Linear Flow
  * Conditional Statements
  * While Loops
* Level 3
  * Procedures
  * Functions


## Level 1

### What is code?
When people talk about [code](https://en.wikipedia.org/wiki/Source_code), imagine a bunch of random words and characters in a [text file](https://en.wikipedia.org/wiki/Text_file).

It's not actually random, but this is what it looks like:

*Psst... Don't spend any time trying to understand this. Just look at it like you would look at a piece of modern art. :)*
```js
var _ref = _asyncToGenerator(regeneratorRuntime.mark(function _callee() {
    return regeneratorRuntime.wrap(function _callee$(_context) {
      while (1) {
        switch (_context.prev = _context.next) {
          case 0:
            console.log('hello world');

          case 1:
          case 'end':
            return _context.stop();
        }
      }
    }, _callee, this);
  }));
```

Let me highlight some interesting characteristics about code:

* code is written in English, [generally](http://softwareengineering.stackexchange.com/questions/1483/do-people-in-non-english-speaking-countries-code-in-english)
* code is often displayed with color (called [syntax highlighting](https://en.wikipedia.org/wiki/Syntax_highlighting)) to indicate special words or characters
* code invents new words that don't exist in the English vocabulary (it's like making memes)
* code is often [cryptic and ugly](https://blog.codinghorror.com/code-isnt-beautiful/)

When you look at code, don't think of it as a series of computer commands. Think of it as a way to communicate a process for getting something done. Computers are all about getting things done, and writing code is how humans can tell computers what to do.

People often talk about [programming languages](https://en.wikipedia.org/wiki/Programming_language). If you don't know what they are, don't worry. I'll explain them later. For now, I just want to focus on the fundamentals of programming.


#### Learning Verification

*Use the scrollbar to hide the answers at the bottom.*

1. Code is written in English. True or False?
2. Writing code is like typing an equation into a calculator. True or False?
3. Syntax highlighting is a way to make special words and characters stand out. It's similar to the way red and green color is often used to highlight postive and negative numbers. True or False?
4. Code can be difficult to read, but that's because some processes are difficult to communicate. True or False?
5. Programmers often invent new words to describe new ways of doing things and use these words in their in code. True or False?
6. Humans use code to tell computers what to do. True or False?

Answers: T, F, T, T, T, T
