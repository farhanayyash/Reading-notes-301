## Read 02 - jQuery, Events, and The DOM

jQuery is a JavaScript file that lets you find elements using CSS selectors and then do something with the elements using jQuery methods. 

```
Function (creates a jQuery object)
$('li.hot')
The jQuery() function has one parameter: a CSS-style selector that finds all li elemenets with a class of hot. 
```

Do something with the elements using jQuery methods:
```
$('li.hot').addClass('complete');
```

- When you select one or more elements, a jQuery object is returned. It is also known as a matched set or a jquery selection.

- Some jQuery methods both retrive information from, and update th contents of, elements. But they do not always apply to all elements. 

- When you create a selection with jQuery, it stores a referece to the corresponding nodes in the DOM tree. It does not create copies of them. 

- A jQuery object stores references to elements. Caching a jQuery object stores a reference to it in a variable. 

- jQuery .ready() method checks that the page is ready for your code to work with. 

```
$(document).ready(function()) {
  // script goes here
});
```
 
 To load jQuery to your page 

 
```
<script src="//ajax.googleapis.com/ ajax/libs/jquery/1.10.2/jquery.min.js"></script> 

<script>
window.jQuery || document.write ('<script src="js/jquery-1.10.2.js11><\jscript>') 
</script> 
```

**6 Reasons for Pair Programming**

[See article](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

Pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code. The Navigator uses their words to guide the Driver but does not provide any direct input to the computer. The Navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code, while scanning for typos or bugs. The Navigator might also utilize their computer as a second screen to look up solutions and documentation, but should not be writing any code.

**Why pair program?**
1. Greater efficiency
2. Engaged collaboration
3. Learning from fellow students
4. Social skills
5. Job interview readiness
6. Work environment readiness
