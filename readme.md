# CSS-ify 
### Mostly Useless!

Some webservices allow custom css but do not allow the hosting of images. In such cases, this script might be useful.
To use this little tool: 

1. replace the Van Gogh image with an image of your choosing and rename it image.jpg.
2. Open index.html in your web browser.
3. Create an html document with one, absolutely-positioned div element, and
4. Copy the generated text as a css rule assigned to that div.

### Example:
This image:

![Van Gogh](./image.jpg)

Can be replaced by an auto-generated CSS rule:
```css
#divID {
	position:absolute;
	box-shadow:
		0px 0px 0 1px rgb(72,105,140),
		0px 1px 0 1px rgb(103,136,167),
		0px 2px 0 1px rgb(139,171,192),
		...;
}
```
(The script above is a truncated example. Those three lines of data would produce the first three pixels of the Van Gogh)