# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


### Screenshot

./design/FireShot1.png
./design/FireShot2.png


### Links

- Solution URL: https://github.com/Vctcode/qr-code-component-main
- Live Site URL: qr-code-vctcode.vercel.app (https://qr-code-vctcode.vercel.app)


## My process
### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

I learned setting CSS variables and using the variables as values of CSS properties. Below highlights the usage.

```
:root {
    --white: hsl(0, 0%, 100%);
    --light-gray: hsl(212, 45%, 89%);
    --grayish-blue: hsl(220, 15%, 55%);
    --dark-blue: hsl(218, 44%, 22%);
}

div.container {
    position: relative;
    margin: 12vh auto 12vh;
    width: 300px;
    height: 470px;
    background: var(--white);
    padding: 15px;
    border-radius: 12px;
    box-shadow: 0 18px 45px -50px var(--dark-blue),
        0  20px 35Px -40px var(--grayish-blue);
}
```


### Useful resources

- https://www.w3schools.com/cssref/css3_pr_box-shadow.asp- This helped me for the box-shadow effect.


## Author

- Website - [Victor Oderinde](https://www.your-site.com)
- Frontend Mentor - [@Vctcode](https://www.frontendmentor.io/profile/Vctcode)
