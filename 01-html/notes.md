# HTML Notes

## Personal notes for HTML learning.

`<h1>` = tag (opening)

`</h1>` = closing tag

`<h1>Hello World</h1>` = element. The entire thing is the element, and the text in between is its content.

`<h1> .... </h1>` = anything within that would be part of the element.

As for headers, it goes all the way up to 6. Once you go past that, there are other workarounds, but not using these types of tags.

`<p>` = paragraph or regular type of text.

### Some void elements

A void element is one that does not have a closing tag and content.

`<hr />` = creates a horizontal line.

This is a special type of tag because it doesn't take any content.

`<br />` = breaks the text at that point and moves to the next line.

### For Lists

`ol` = ordered list

`ul` = unordered list

Within them, each new item must be a `li` element:

`<li> .... </li>`

example:
```html
<ul>
  <li>¾ cup warm milk</li>
  <li>2 ¼ teaspoons yeast</li>
  <li>¼ cup granulated sugar</li>
  <li>1 egg plus 1 egg yolk</li>
  <li>¼ cup butter</li>
  <li>3 cups bread flour</li>
</ul>
```


`<a>` = anchor tag.
    example : `    <a href = "https://www.linkedin.com/in/adamelshanawany/">My  LinkedIn </a>`

Allows us to create hyperlinks, whether that be for a website, email address, file, etc.

`<img />` = image tag.
    example: `<img src="https://raw.githubusercontent.com/appbrewery/webdev/main/kitten.jpeg" alt="kitten held in hand" />`

Allows us to show an image element, but we must input the image source.

Note:  Skipped 3.4 because too simple for me to be bothered to complete it.


### File  Paths
Typically relative paths are used. So the path to get to that file in specific to where the file you are currently working on is at.

./ = Within our current directory
../ = Going up a level