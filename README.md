# Notes


**jQuery**

**jQuery is zero-indexed**

* Add jQuery to a project by adding the following code in the head section:

**CDN**
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
```

**If downloaded on computer**

```html
<script src="jquery-3.4.1.min.js"></script>
```

* The following code needs to be added to a project:

```html
<script>
$(document).ready(function() {
});
</script>
```

The browser will run any JavaScript inside a script element, including jQuery.

The code in the function will run as soon as the page loads.

* **jQuery functions** start with a $

* jQuery selects HTML elements using selectors and then something is done to that/those elements 


* **Animate.css** library - add to your code:
```html
npm install animate.css --save
```

In html file, add on the head section:
```html
<head>
  <link rel="stylesheet" href="animate.min.css">
</head>
```

* **Selecting elements**
* Using jQuery means that we don't have to use methods such as getElementById(),
getElementsByName(), getElementsByClassName(), getElementByTagName()


* **Select elements by their id and make it fade out:**

```html
$("#elementToSelect").addClass("fadeOut");
```

* **Select elements by their class and make fade out:**

```html
$(".btn").addClass("fadeOut");
```

* **Select elements by their type and make fade out:**

```html
$("button").addClass("fadeOut");
```

* **Target the same element with multiple jQuery selectors:**

```html
  $("button").addClass("animated shake");
    $(".btn").addClass("animated bounce");
    $("#target1").addClass("animted fadeOut");
```

* **Remove classes from an element using the removeClass() function:**

```html
$(button).removeClass("animated shake");
```

* **Change the CSS of an element using the .css() function:**

* change colour of button to pink
```html
$("#button1").css("color", "pink");
```

* **Disable buttons** - (make them non-clickable)

* **Disable the button with id of button1:**

```html
$("#button1").prop("disabled", true);
```

* **Add text and HTML tags inside an element using the .html() function:**

* Add the word 'hello' to an h3 element:

```html
$("h3").html("<em>Hello</em>");
```

* **Alter text of an element using the .text() function:**

```html
$("h3").text("Hello);
```

* **Remove an element using the .remove() function:**
Remove the button with id of 'like':

```html
$("#like).remove();
```

* **Append elements to another element using appendTo() function:**
Add button with id of 'love' to h3 element with id of 'h3one':

```html
$("#love").appendTo("#h3one");
```

* **Clone or make a copy of an element using the clone() function:**
Copy a smiley element with id of smiley and add it to an h3 element with id on h3one:

```html
$("#smiley).clone().appendTo("#h3one);
```

* **Target/access the parent of an element using the parent() function**

* Every HTML element has a parent element from which it inherits properties.
* **parent()** allows you to access the parent of the selected element

* Give the parent element of the element with id #left-well a pink background:

```html
$("#left-well").parent().css("background-color", "pink")
```

* **Target/access the children of elements using the children() function:**
* HTML elements can have children. These children inherit the properties of their parents.

* Give the children of the left-well element a background of pink:
```html
$("#left-well").children().css("color", "pink")
```

* **Target a specific child element using the target:nth-child(n) CSS selector:**
* Give the third element in each well the animated shake class:

```html
$(".target:nth-child(3)").addClass("animated shake");
```

* Give the third element in each well the bounce class:

```html
$(".target:nth-child(3)").addClass("animated bounce");
```

* **Target elements based on their positions using the :odd**
**and :even selectors:**













* **Make buttons bounce:**

```html
$("button").addClass("animated bounce");
```

* **Make buttons shake:**

```html
    $("button").addClass("animated shake");
```

