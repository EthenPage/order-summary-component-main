# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj).

-24 March 2022

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Special Thanks](#special-thanks)
- [Date](#date)



## Overview

### The challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![](./finished/desktop-version.png)

### Links

- Solution URL: [Solution](https://www.frontendmentor.io/solutions/order-summary-card-ByVMnUjM9)
- Live Site URL: [Live](https://ethenpage.github.io/order-summary-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learnt

- vertically and horizontally centered items
- use flexbox to the body to center the card.
- after that, add `min-height: 100vh` to body because Flexbox aligns child items to the size of the parent container.

```css
body{
  display: flex;
  flex-direction: column;
  align-items: center;
  min-height: 100vh;
  justify-content: center;
}

main{
  width: 324px; /* or what you need */
}
```


## Author

- Name - Mirza Monirul Alam (Ethen).
- Frontend Mentor - [@EthenPage](https://www.frontendmentor.io/profile/EthenPage)

## Special Thanks 

- [Deniel Den](https://www.frontendmentor.io/profile/denielden).

## Date

- 25 March 2022