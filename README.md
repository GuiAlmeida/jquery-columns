jQuery ul (unordered lists) Columns
=======

jQuery plugin that takes any unordered list and splits it into a specified number of columns, version 1.0.0.

Really easy to use. First include jquery. Then include jquery.columize-unordered-list.js

Here's a live example of how I use this script:

http://jsfiddle.net/EebVF/5/

-------

Here's a quick example of how you could apply this across all uls with a class of "cols2"

    $(document).ready(function() {
      $('ul.cols2').columnize(2)
    });

You would then want to apply your css: 

    ul.cols2 { 
      width: 50%; 
      float: left; 
    }
    
And you're done!
