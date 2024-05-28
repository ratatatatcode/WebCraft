<b>We can tackle centering divs later, but have you considered using Google Fonts to add some style to your project. It's pretty easy to set up.</b>
* Search for a font on <a href="https://fonts.google.com/">Google Fonts</a>
* Select a font and click it.
* Click "Get Font" then choose "Get embeded code".
* Under "Embed code," select the "@" symbol (usually labelled "Import").
* Then follow how I import it in the css file.
``` css
/* styles.css */
.box-container {
    font-family: "Bebas Neue", sans-serif;
    border: 2px solid black;
    border-radius: 30px;
    padding: 15px;
    background-color: white;
}
```
<br>

<b>Now, let's say you have the following HTML code inside your HTML file.
<br>You want to center the box-container within the container.</b>
``` html
<!-- index.html -->
<body>
    <div class="container">
        <div class="box-container">
            <p>Hello World!</p>
        </div>
    </div>
</body>
```
<br>

<b>There are commonly used ways to center a div or any other element.</b>
<br>

<b>FLEXBOX</b>
<br>I recommend this <a href="https://flexboxfroggy.com/">Flexbox Froggy</a> for learning flexbox.
``` css
.container {
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    width: 100%;
    background-color: #f2f2f2;
}
```
<br>

<b>GRID</b>
<br>I recommend this <a href="https://cssgridgarden.com/">Flexbox Froggy</a> for learning grid.
``` css
.container {
    display: grid;
    place-items: center;
    height: 100vh;
    width: 100%;
    background-color: #f2f2f2;
}
```
<br>

<b>POSITION</b>
<br>I would not recommend this unless you are going to create a pop-up box or form.
<br> You can refer to the documentation for <a href="https://learnlayout.com/position">POSITION<a/>.
``` css
.container {
    position: relative;
    height: 100vh;
    width: 100%;
    background-color: #f2f2f2;
}

.box-container p {
    position: absolute;
    font-family: "Bebas Neue", sans-serif;
    border: 2px solid black;
    border-radius: 30px;
    background-color: white;
    padding: 15px;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}
```
<br>

<b>Responsive design is a complex subject, but there are some great resources available online. While I can't help you with responsiveness specifically, I can recommend a few if you'd like to learn more about it on your own.</b>
* <a href="https://www.youtube.com/watch?v=TUD1AWZVgQ8">WebDevSimplified | Top 10 Advanced CSS Responsive Design Concepts You Should Know</a>
* <a href="https://www.youtube.com/watch?v=K24lUqcT0Ms">Slaying The Dragon | Master Media Queries And Responsive CSS Web Design Like a Chameleon!</a>
<br>

<a href="https://medium.com/geekculture/learn-css-by-playing-games-cf70a79a38">Learn CSS By Playing Games 👾</a>
<br>The games here might be helpful for learning web development concepts, including potentially some related to responsiveness.
<br>

Additionally, I hope your study of responsiveness covers concepts like media queries, flex-wrap, flex-direction, max-width & min-width, calc(), and grid-columns.
