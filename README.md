# Prototype Picker Microsite

codename Picklejar

## Requirements

  * Ruby 1.9+
  * [Node.js](http://nodejs.org)
  * [compass](http://compass-style.org/): `gem install compass`
  * [bower](http://bower.io): `npm install bower -g`

  I ran into the following issue and was fairly confused for 30 minutes. You can potentilly save yourself some time by rolling back to Compass 0.x I didn't have to roll back Sass to fix it. Sass 3.4+ seems to be compiling fine. 
  [SCSS compiles but resulting CSS-file incomplete](http://foundation.zurb.com/forum/posts/18630-scss-compiles-but-resulting-css-file-incomplete)

## Overview

Here's a working document on the concept: [Picklejar Google doc](https://docs.google.com/a/gophilosophie.com/document/d/1txsAV2hykBMdlAqyKUFkovxdf1lfZElyhrOcRGq5F_c/edit)

The idea is that a user can input what they want to test and the app will suggest what type of prototype to use.