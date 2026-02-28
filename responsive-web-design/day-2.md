# Day 2 – Elements & Attributes
## 2.28.26
### Element = `<tag>`Content`</tag>`
Tag = the code surrounding an element, such as `<h1>` `</h1>`

Content = the stuff that goes with the tag(s)

Element = tag(s) + content

*Void Element = no closing tag. Example: `<img>` Some code like Prettier will include `/` in a void element, but HTML does not.

### Attributes
src = specify image location

alt = image descripton

Example: `<img src="https://image_link.jpg" alt="image description" />`

**Overall format:** `<element attribute="value"></element>`

href = URL for a hyperlink (think, "Hey, let's reference this URL!")

target = the text you want to hyperlink (t for target, t for text)

#### Example: 
Code: `<a href="https://frontendfrequencies.dev/" target="_blank">Check out my developer project!</a>`  
Rendered Output: <a href="https://frontendfrequencies.dev/" target="_blank">Check out my developer project!</a>

`target="_blank"` opens the link in a new browser tab (super cool!)

### Boolean Attributes:  
- disabled
- readonly
- required
