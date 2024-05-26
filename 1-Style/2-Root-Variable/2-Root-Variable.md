<b>DECLARATION OF CSS VARIABLE</b>
<br>This is a good practice when you're creating your own project.
<br>

For example, you can compile all the colors you need.

``` css
:root {
    --main-color: pink;
    --secondary-color: black;
}

*,
body {
    margin: 0;
    padding: 0;
}

h2 {
    color: var(--main-color);
}
```
