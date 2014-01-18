---
title: "How can I practice coding outside of Codecademy - JavaScript Edition"
---

Practicing Javascript out of Codecademy is just a breeze. Here’s a step-by-step guide about writing Javascript and its plugin jQuery on either your local machine or using online editors:

### On your local machine:

1. Open up a text editor of your choice. Check out [this article][1] for some good choices.
2. Write up a program of your choice. The ["Hello World" program][2] is a popular choice for a first trial.
3. Save it as a JavaScript file. This means including the `.js` file extension, i.e. `"HelloWorld.js"`. 
4. Create a HTML document. Follow [these directions][3] to make one.
5. **(Optional)** To practice jQuery, add the following to your HTML file:
```html
<!--These tags should be in exactly this order.-->
<link href="http://ajax.googleapis.com/ajax/libs/jqueryui/1/themes/smoothness/jquery-ui.min.css" rel="stylesheet" type="text/css" />  <!--An additioanl CSS file bundled with jQuery UI -->
<script src = “http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js”></script>  <!--jQuery 1.9.1 --->
<script src="http://ajax.googleapis.com/ajax/libs/jqueryui/1/jquery-ui.min.js"></script>  <!--jQuery UI 1.10.1-->
```
6. Include your new script file to the HTML file from step 4. Below is an example using the `"HelloWorld.js"` script:
```html
<script src=”PathToYourJSFile/HelloWolrd.js”></script>  <!-- Your HelloWorld.js --> 
```
7. Open up a browser of your choice. Press `Ctrl + O` and locate your HTML file with your linked JavaScript file. Your `console.log` statements will appear in the browser's developers console. If you open your JavaScript file instead within the browser, then it will just share your source code in the browser.

### Using an online tool:
1. If you want to just practice writing JavaScript programs, you can use [Codecademy Labs](http://labs.codecademy.com).
2. These are some online tools: 
  - [JSBin](http://www.jsbin.com)
  - [JSFiddle](http://www.jsfiddle.net)

Make sure to save the URL, that appears when you click “Save”, in your bookmarks. **Note**: Saving is automatic in JSBin.

  [1]: article-from-#115
  [2]: http://en.wikipedia.org/wiki/Hello_world_program
  [3]: article-from-#110
