## Millioncities *- Official Coding Conventions -*

This is the official guide on how to write code for millioncities.com

#### Tools used by millioncities
* `PHP / HTML / JAVASCRIPT (jQuery)`
* `Laravel` php mvc framework
* `Backbone` js mvc
* `Less` instead of css
* `Grunt` (node js based task manager)
* `Git` for version control
* `Trello` store things todo

#### Javascript
* Use `camelCase` (first letter small) for variable and function names
* Prefix *jQuery* variables is $, eg. `var $someSelector = $("#selectById")`
* Make sure your code lints (check the jshint configuration for more details)

#### HTML/Less
* Use dashes on html attributes and css class names 

#### PHP
* Use `_` (underscore) for variable names, eg. `$new_var`
* Class names should use `CamelCase` with first letter capital
* Functions and methods should use `camelCase`

#### How to comment
Always comment using double slash `//`, never use multiline comments on any file (JS, PHP, LESS etc.).
This allows to docco to parse the comments and create a documentation.
Be as expressive as you can on the comments (always write code as if the coder afterwards is a crazy phycopath)

**How to write comments for docco?**

Docco parses comments according to [markdown](http://daringfireball.net/projects/markdown/syntax) syntax.
For more details on docco check their [homepage](http://jashkenas.github.io/docco/).
Also check out a [demo](http://underscorejs.org/docs/underscore.html) of the kind of docs produced by docco.
Most commonly used markdown notation:
* `**Word**` for bold
* `*Word*` for italics
* For `<h1>` headers write write the header comment `H1 Header` followed by `========` on the next line
* For `<h2>` headers write write the header comment `H2 Header` followed by `--------` on the next line
* `[link text](http://www.somelink.com)` for links

#### Files
* Name files using `camelCase` as in javascript


*__NOTE__*: always follow library conventions if neccessary (eg. Laravel file naming)
*__Note__*: the above conventions do not apply to downloaded libraries which should remain as they are
