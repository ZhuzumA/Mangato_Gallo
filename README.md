## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- View the Cards Collection with Price and Buy Button 
- View Kontakt information
- Be able to reach all Pages: About, Collection, Home
### Screenshot

![](./main.png)
![](./collection.png)
![](./collection_on_hover.png)
![](./main_on_hover.png)
![](./collection_resp.png)
![](./about.png)


### Links

- Source Code: [GitHub Repo](https://github.com/ZhuzumA/Mangato_Gallo)
- Live Site URL: [Mangato & Gallo](https://your-live-site-url.com)

### Built with

- Semantic HTML5 markup
- SASS Framework
- Flexbox
- Responsive Media Queries


### What I learned

For the first time I used SAAS Framework. I also found out how to set filter property to control the shadows of an element. I also learned how to set a background property of the entire element with dark gradient.

```css
body {
	font-family: $font-family-serif;
	background: linear-gradient(rgba(0, 0, 0, 0.9), rgba(0, 0, 0, 0.9)), url("../resources/about.jpg") no-repeat center center fixed;
}
```
```css
a:hover {
			filter: drop-shadow(2px 0px 3px $beige-hover);
		}
```
```scss
$beige-hover: rgba(249, 203, 201, 0.817);
//Breakpoints
$sm-viewport: 560px;
```


## Author

- Website - [Zhuzum](https://github.com/ZhuzumA)
- Gmail - [@gmail](zhuzum@gmail.com)


