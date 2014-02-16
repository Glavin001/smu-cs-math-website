
# LESS

[LESS](http://lesscss.org/) is a language for writing **less css**.

This directory is for all less files written for the SMU CS and Math Society
website. 

## Including your LESS

If you wish to make a less file simply create the file and import in the 
include.less file contained within the directory. Then include 
`css/compiled.less.css` in your web page. 

For example, a file named `foobar.less` is imported within the 
`include.less` with the corresponding import directive :

```less
@import 'foobar'
```

## Compiling your LESS

So here's the deal, LESS is a language layer on top of CSS. The web runs on 
CSS, so all of these other fancy things you here about must at some point
translate to CSS. 

You can compile your LESS to CSS with grunt using the grunt plugin, 
[grunt-contrib-less](https://github.com/gruntjs/grunt-contrib-less). There are 
two modes specified, `develop` and `release`. 

**To Compile your LESS run :** `grunt less:develop` or `grunt less:release`.

For debugging you purposes you should use `grunt less:develop`. 

I challange you to figure out the difference by checking out [grunt](gruntjs.com), 
and [grunt-contrib-less](https://github.com/gruntjs/grunt-contrib-less) 
and tracking down the configuration differences in the building. 


