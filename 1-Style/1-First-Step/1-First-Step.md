<b>You might notice that I keep using this:</b>
``` css
*,
body {
    margin: 0;
    padding: 0;
}
```
<b>This CSS code is used to remove all default spacing (margins and padding) from all elements and the main body of the web page. This is often done as a first step in web design to have a clean slate, allowing the designer to add custom spacing as needed.</b>
<br><br>

Try removing removing the margin, padding: 0;
<br>Then create a container and change the background color to blue with <b>100vh and 100vw/100% (default size for desktop).</b>
``` html
<!-- index.html -->
<div id="container"></div>
```

``` css
/* styles.css */
*,
body {
}

#container {
  height: 100vh;
  width: 100%;
  background-color: blue;
}
```
<br>

<b>You can call elements using in CSS:</b>
* h1 (directly calling the tag)
* .className - use to call a class attribute (class="className)
* #idName - use to call an id attribute (id="idName)
