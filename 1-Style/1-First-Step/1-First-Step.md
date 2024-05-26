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

<!-- # - calling "id" attribute from the HTML -->
#container {
  height: 100vh;
  width: 100%;
  background-color: blue;
}
```
<br>

<b>Run the HTML file where this md resides. It will show you the output.</b>
