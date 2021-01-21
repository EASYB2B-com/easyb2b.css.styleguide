#ezyB2B CSS Styleguide
*****

_This styleguide is for internal use of ezyB2B_

######Install with Bower

<pre>bower install --save git@bitbucket:ezyb2b/styleguide.git</pre>


###Table of Contents
***

1. CSS
  1. Formatting
  
  

####CSS
***

#####Formatting

* two (2) space indents, no tabs;
* When using multiple selectors in a rule declaration, give each selector its own line.
* a space before our opening brace ({);
* properties and values on the same line;
* a space after our property–value delimiting colon (:);
* each declaration on its own new line;
* the opening brace ({) on the same line as our last selector;
* our first declaration on a new line after our opening brace ({);
* our closing brace (}) on its own new line;
* each declaration indented by two (2) spaces;
* a trailing semi-colon (;) on our last declaration.

######Incorrect

<code>
.foo, .foo--bar, .baz
{
display:block;
background-color:green;
color:red }
</code>

######Correct

<code>
  .foo,
  .foo--bar,
  .baz {
    display: block;
    background-color: green;
    color: red;
  }
</code>



  