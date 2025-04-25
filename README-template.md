# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

This is a simple recipe page. The page can fit into all screen sizes, doesn't matter the size. The recipe is easy to follow and has clean layout

### Links

- Solution URL: (https://simple-rec1pe-page.netlify.app/)
- Live Site URL:(https://simple-rec1pe-page.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- div
- width
-height
- Media queries for responsiveness


### What I learned

I learnt how to use media queries to make my page look clean on the small screen. It was so cool to figure it out and learn how to adjust the container and the image to fit the screen.

I also learnt how to style the numbers on the ordered list.
```
ol li::marker {
  color: hsl(14, 45%, 36%);
  font-weight: bold;
}
```

```html
<table>
        <tr>
          <td>Calories</td>
          <th>277kcal</th>
        </tr>

        <tr>
          <td>Carbs</td>
          <th>0g</th>
        </tr>

        <tr>
          <td>Protein</td>
          <th>20g</th>
        </tr>

        <tr>
          <td>Fat</td>
          <th>22g</th>
        </tr>
      </table>
    </div>
```
```css
.container table {
  width: 100%;
}

.container th,
td {
  text-align: left;
  border-bottom: 1px solid #ddd;
  padding: 8px;
}
.attribution {
  font-size: 11px;
  text-align: center;
}
.attribution a {
  color: hsl(228, 45%, 44%);
}



### Continued development

Media queries still give me a bit of a headache, I want to focus on them and also the positioning for the elements. 

### Useful resources

- W3 Schools HTML tutorial (https://www.w3schools.com/html/default.asp) - This is an amazing website which helped me figure out how to create tables

- W3 Schools CSS tutorial (https://www.w3schools.com/css/default.asp) - This helped me for styling and the media query



## Author

- Website - Resego Motlhasi (https://simple-rec1pe-page.netlify.app/)
- Frontend Mentor - @resegoreey(https://www.frontendmentor.io/profile/resegoreey)
- Github - @resegoreey(https://github.com/resegoreey)


