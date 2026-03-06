# Day 6 - HTML practice, Meta Elements & Open Graph Tags
## 3.5.26
### Basic HTML Element
`<element attribute="value">inner text</element>`

### HTML Practice
<a href="https://github.com/frontendfrequencies/Home/blob/a486624c46ec510e79eea634e8058b0398d4fbb5/responsive-web-design/day-6-bookstore.html" target="_blank">Bookstore Page - Raw Code</a>  
<a href="https://frontendfrequencies.dev/responsive-web-design/day-6-bookstore" target="_blank">Bookstore Page - Rendered Output</a>

### Meta Elements
- `<meta>`
- Void element
- `<meta title="description" description="This page is about such and such">` helps with SEO (Search Engine Optimization)
- The text in the description attribute will appear in the web search results.

### Open Graph Tags
Tell social media platforms how to display your page when it’s shared, like the title, image, and link.

OG Property Examples:
- Title: `<meta content="Frontend Frequencies" property="og:title" />` lists the name of your content
- Type: `<meta property="og:type" content="website" />` tells social media "this is a website"
- Image: `<meta content="https://raw.githubusercontent.com/frontendfrequencies/Home/main/assets/logo.png" property="og:image" />` displays the image on social media (good to use your logo!). Recomended: 1200 by 630 pixels
- URL: `<meta property="og:url" content="https://frontendfrequencies.dev/" />` shares url with social media (like your home page) include thr FULL URL

