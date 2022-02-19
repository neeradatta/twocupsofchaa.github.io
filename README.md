# twocupsofchaa.github.io

The main site for Two Cups of Chaa.

## Run Local Server

### Updating Source Code

Run this command `npm run build` to build the source code only. Run this command `npm run watch` to build and watch for changes related to the source code (src folder). Use this if you are making changes to the core JavaScript.

### Run Server

Run this command `npm run serve` to run an instance of the web site. Use this if you are only making changes to the pages/posts.

### View Dev Environment

Open https://127.0.0.1s:4000 in a browser.

## Overview

### Category Folder

Put a file for each unique category used in your posts.

### Images Folder

Put you image references here. Put them in SEPARATE FOLDERS please.

### _Posts Folder

This is the main folder you will add to. Copy an old post and start growing your site.

<img class="img-rounded" src="/images/about/icon1.png" alt="Two Cups Of Chaa" width="100">
<img class="img-rounded" src="/images/about/icon2.jpg" alt="Two Cups Of Chaa" width="100">
<img class="img-rounded" src="/images/about/icon3.jpg" alt="Two Cups Of Chaa" width="100">
<img class="img-rounded" src="/images/about/icon4.jpg" alt="Two Cups Of Chaa" width="100">

## Jekyll Template

Using the [Jekflix](https://jekflix.rossener.com/) template.

## Help

### Links vs Images

Images inherit from a link format, since it's a link to the image. A link format is `[Content]` followed by `(URL)`. For a link, the `Content` is what is displayed, where the `URL` is the link for the element. Placing a `!` at the beginning of the link will change the output to an image, where the `Content` is now the alt text of the image. _(Examples shown below)_

* Link (a) Element - `[Link to Dattabase Site](https://dattabase.com)`
* Image (img) Element - `![Banister decorated with flowers](\images\portfolio\photo\decor\banister.jpg)`

#### Image Link

To create an image and have it function as a link, simply place the image in the `Content` area of the link template. _(Example shown below)_

* `[![Banister decorated with flowers](\images\portfolio\photo\decor\banister.jpg)](https://dattabase.com)`

* `![Banister decorated with flowers](\images\portfolio\photo\decor\banister.jpg)`
  `[Click to go to Etsy Shop](https://www.etsy.com/shop/TwoCupsOfChaa)`
