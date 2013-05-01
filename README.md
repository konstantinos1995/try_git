## Millioncities *- Official Coding Conventions -*

This is the official guide on how to write code for millioncities.com

#### Javascript
* Always use `camelCase` (first letter small) for variable and function names
* Prefix *jQuery* variables is $, eg. `var $someSelector = $("#selectById")`
* Make sure your code lints (check the jshint configuration for more details)

#### HTML/CSS
* Use dashes on html attributes and css class names 

#### PHP
* Use `_` (underscore) for variable names, eg. `$new_var`

#### How to comment
Always comment using double slash `//`, never use multiline comments.
This allows to docco to parse the comments and create a documentation.
Be as expressive as you can on the comments (always write code as if the coder afterwards is a crazy phycopath)

**How to write comments for docco?**

Docco parses comments according to [markdown](http://daringfireball.net/projects/markdown/syntax) syntax.
For more details on docco check their [homepage](http://jashkenas.github.io/docco/).
Also check out a [demo](http://underscorejs.org/docs/underscore.html) of the kind of docs produced by docco.
Most commonly used markdown notation:
* `**Word**` for bold
* `*Word*` for italics

#### Files
* Name files using `camelCase` as in javascript
