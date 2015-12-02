# bob-ross-lipsum

Phrases from Bob Ross' [Joy of Painting](https://en.wikipedia.org/wiki/The_Joy_of_Painting), alternative to Lorem Ipsum text, inspired by http://bobrosslipsum.com/

## use

```
var happyTrees = require('bob-ross-lipsum')
// One phrase
console.log( happyTrees() ) // 'Paint anything you want on the canvas. Create your own world.'
// More than one phrase
console.log( happyTrees(3) ) // 'I like to beat the brush. Work on one thing at a time. Don\'t get carried away - we have plenty of time. This is your world, whatever makes you happy you can put in it. Go crazy.'
```