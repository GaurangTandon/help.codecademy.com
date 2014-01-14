---
title: How can I practice coding outside of Codecademy - JavaScript Edition
---

Practising Javascript out of Codecademy is just a breeze. Here’s a step-by-step guide about writing Javascript and it’s plugin jQuery on either your local machine or using online editors:

### On your local machine:

1. Open up a text editor of your choice ([Notepad++ (Windows)](http://notepad-plus-plus.org/), [gedit (Linux)](https://wiki.gnome.org/Apps/Gedit), [TextWrangler (Mac)](http://www.barebones.com/products/textwrangler/) and [KomodoEdit (all)](http://www.activestate.com/komodo-ide) are some good choices).
2. Write up a program of your choice (For a trial, copy the code you did [here in this exercise](http://www.codecademy.com/courses/javascript-beginner-en-x9DnD/0/7?curriculum_id=506324b3a7dffd00020bf661)).
3. Now save it with a name, say, “**Game.js**”. Make sure you include the **.js** at the end of the file name. Also, in the option of the file type, choose “Save as all file types”. 
4. Writing jQuery requires you to write the following lines in your HTML file:

`
    <!--These tags should be in exactly this order.-->
    <link href="http://ajax.googleapis.com/ajax/libs/jqueryui/1/themes/smoothness/jquery-ui.min.css" rel="stylesheet" type="text/css" />  <!--An additioanl CSS file bundled with jQuery UI -->
    <script src = “http://ajax.googleapis.com/ajax/libs/jquery/1/jquery.min.js”></script>  <!--jQuery 1.9.1 --->
    <script src="http://ajax.googleapis.com/ajax/libs/jqueryui/1/jquery-ui.min.js"></script>  <!--jQuery UI 1.10.1-->
`

5. Now include the following lines to connect your **index.html** file to your **stylesheet.css** (if any) and **Game.js**.

`
    <link href = "PathToYourCSSFile/stylesheet.css" rel = "stylesheet" type = "text/css" /> <!--Your CSS file, if any-->
    <script src=”PathToYourJSFile/Game.js”></script>  <!-- Your Game.js file we made--> 
`

6. That’s it. Your file is ready. Now run the **.html** to which you linked your **.js** file using a browser. Your `console.log`s would go in the browser console (press F12 in the browser window). Perhaps, replace the `console.log`s with `alert`s as the `console` thing gets tricky, because if say `console.log("Codecademy");` finishes execution and then the browser console is opened, the "Codecademy" log might vanish in some browsers. Also note that if you open your **.js** file directly using a browser, you would see the code you wrote rather than the output.

### Using an online text-editor:

1. These are some online-text editors : [JSBin](http://www.jsbin.com) and  [JSFiddle](http://www.jsfiddle.net). Make sure to save the URL, that appears when you click “Save”, in your bookmarks (Note: Saving is automatic in JSBin).
