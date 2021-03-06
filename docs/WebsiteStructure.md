
# SMU Math and CS Website Structure

This document outlines the structure of the SMU Math and CS Website. 

## /app

The `app` directory stores the static website to be servered to the 
client. Raw HTML pages may be placed into this directory.

#### Raw javascript 

may be placed in `/app/scripts` though of course, we recommend you 
use [Browserify](http://browserify.org/). Please attempt to implement 
[javascript namespacing](http://addyosmani.com/blog/essential-js-namespacing/)
and avoid populating the global namespace with junk. 

#### Raw CSS 

may be placed in `/app/style` though we recommend you check out 
something **more powerful**, **easy to use**, and all around **sexier**
like [LESS](http://lesscss.org/) (Dawson's favorite!) or 
[Sass](http://sass-lang.com/).

Support for everything discussed above will be added soon!

#### No :filetype Please!

- jade
- less
- sass
- coffeescript 
- ect ...

## /test

The `test` directory contains our site tests.  

We have yet to decide on a testing framework, though several nice frameworks are [Mocha](http://visionmedia.github.io/mocha/), [Jasmine](http://pivotal.github.io/jasmine/), and [qUnit](http://qunitjs.com/). 

Notice the first two are hosted on Github! Why don't we do something like that? Check this sort of this out [here](http://pages.github.com/).
