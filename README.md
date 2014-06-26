Why So SSO LnL

## Setup RevealJade

1. Clone Repo
2. Install NodeJS ~0.10 if you don't have it
3. `npm install -g grunt bower`
4. `npm install`
5. `bower install`
6. `grunt serve`
7. Checkout the presentation at localhost:8000
10. Enjoy!

## The Mixins

### ulSlide

Takes a `String:`title and `Array:`list arguments to create a slide with an uordered list

### olSlide

Takes a `String:`title and `Array:`list arguments to create a slide with an ordered list

### slide

The basis of all slides and accepts a Jade block

### bigTitleSlide

Takes a `String:`title and accepts a jade block to produce a slide with a `<H1>` title

### littleTitleSlide

Takes a `String:`title and accepts a jade block to produce a slide with a `<H3>` title
