**jQuery**

* Add jQuery to a project by adding the following code in the head section:

**CDN**
```html
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
```

**If downloaded on computer**

```html
<script src="jquery-3.4.1.min.js"></script>
```

<script>
$(document).ready(function() {
});
</script>

The code in the function will run as soon as the page loads.

* **jQuery funtions** start with a $
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


* **Make buttons bounce:**

```html
$("button").addClass("animated bounce");
```

* **Make buttons shake:**

```html
    $("button").addClass("animated shake");
```

