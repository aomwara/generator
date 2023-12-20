﻿# cryptopunk nft generator
This is a console app to generate 800,000 crypto punks using javascript

[Check out my blog post for more details](https://dev.to/victorquanlam/generate-879-120-cryptopunk-nfts-with-javascript-nodejs-command-line-app-step-by-step-10hp)

## install canvas package

```` npm install ````

## run index.js or build

````node index.js ````

## limit outputs eg: 100 images

````node index.js 100````

## Troubleshot

If you have 'npm error' when you install canvas package on MAC OS, try this cmd:
```
brew install pkg-config cairo pango libpng jpeg giflib librsvg pixman
``` 
More informations [here](https://github.com/Automattic/node-canvas)
