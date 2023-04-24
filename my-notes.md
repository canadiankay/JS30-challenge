# Welcome to my version of JavaScript 30 practice projects, a free course created by Wes Bos to practice vanilla JS skills.

## To do list
- complete a project a day
- create a website that hosts all of these projects (e.g. [like this](https://kellychi22.github.io/JavaScript30/) )~
- update and customize each challenge
  - Day 1: add duff or nasheed sounds and change background ✅
  - Day 2: change background, display digital clock and give users ability to switch between digital and analog mode
  - Day 3: change background, add more properties

### Day 1: JS Drum Kit
- `keydown` event --> listen for pressed keys
- HTML `data-*` Global Attribute --> to give a custom attribute
- `HTMLMediaElement.play()` method --> to play an audio/video element
- `HTMLMediaElement.currentTime` property --> gives us the current time
- `transitionend` DOM event --> listen for the end of a transition event

### Day 2: JS and CSS Clock
- DOM `setInterval()` property
- `transition-timing-function` and `transform-origin` CSS properties

### Day 3: 
- you can JS to update CSS variables
- `<input type="range">` HTML property that shows a line-bar that you can drag
- set a variable in `:root` in *CSS styles* then use this format to use the variable: `var(--*variable name*)`
- `CSSStyleDeclaration.setProperty` used to update the CSS styling


### Day 4:
- `console.table` instead of `console.log` to display results in a table
- filter method loops over each item in an array 
- map method takes in an array, does something, and returns a new array of the same length
- sort method sorts/compares two items at a time by criteria, return 1 (for item that satisfies) and -1 (for item that doesnt) moving them up and down the array (index-wise)
- reduce method 
  - one of the most flexible methods
  - will take in an array and allow us to build on each value in an array and cleaner than using a 'for' loop to add/subtract +=/-= an initial value and grow on it by giving us a running total after looping through each item in an array
  - you can shorten the way you apply multiple methods to set a data (see code)
  - e.g. convert list of names into strings `const boulevards = links.map(link => link.textContent);` then filter list to only include 'de' names `const deNames = boulevards.filter(blvd => blvd.includes('de'));` --> instead you can do the following: 
    `const deNames = links`
                      `.map(link => link.textContent)`
                      `.filter(blvd => blvd.includes('de'));`
- split method takes in a pattern and turns a string into a new array of substrings without changing the original string
