# CSS Notes

Personal notes for CSS learning.'

3 different ways to style with CSS (Cascading Style Sheets)

Inline, Internal, & External

The way it work is by having our CSS property such as `background` then the value of the property `blue`

### Inline
<hr />
Typically for used for testing as its for each tag, so one line or hitting on section to test for example only <br />
Else it will become too crowded and code won't be clear.

```html
<html style = "background:blue"> 
    .....
</html>
```

### Internal
<hr />
Open style tag and closing style tag, in which all of our CSS would go in between there <br />

But now instead of it being inside the element we have to add a `selector` that goes outside the curly braces `{ }`, and the CSS in between. From there we target as many elements in the document and anywhere within that file.



```html
<html>
    <head>
        <style>
            html{
                background:red;
            }
        </style>
    </head>
</html>
```
Useful when it's only to one document so its purley limited to that one page, so if working on multiple pages, it's not as good as you have to copy all the stylying to each file and at that point it's better to have a blueprint ...

### External
<hr />

This now lives in a different file such as `style.css` <br />
However now wwe have to link it with our html file, which is done via

```html
<html>
    <head>
        <link
            rel = "stylesheet"
            href = "./style.css"
        />
    </head>
</html>


```
