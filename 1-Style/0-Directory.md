<b>Internal CSS</b>
<br>Adding styles by placing them within the head tag of the same HTML file.
<br>
``` html  
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="main.css">

    <style>
        *, body {
            margin: 0;
            padding: 0;
        }
    </style>
</head>
<body>
</body>
</html>
```
<br>

<b>Inline Styling</b>
<br>
``` html  
<h2 style="margin: 30px;">I'm blue</h2>
```
<br>

<b>External CSS</b>
<br>Create a CSS file (e.g., styles.css) in the same directory as your HTML file and reference it using a <link> tag in the HTML's <head> section.
<br>
``` html
<!-- index.html -->  
<link rel="stylesheet" href="styles.css">
```
``` css
/* styles.css */
*,
body {
    margin: 0;
    padding: 0;
}
```
