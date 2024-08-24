# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/akil4/qr_code_component](https://github.com/akil4/qr_code_component)
- Live Site URL: [https://akil4.github.io/qr_code_component/](https://akil4.github.io/qr_code_component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Font Awesome (for logo)

### What I learned

Was confused on how to center the card in the display. I tried to position it and failed, later realised flex makes it easier.

```html
<body>
    <main>
        <div class="card">
            <div class="qr-container">
                <img src="qrcode_github.com.png" alt="A QR Code">
            </div>
            <h1>akil4</h1>
            <div class="paragraph">
                <p>Scan QR code to visit visit my github</p>
                <i class="fa-brands fa-github"></i>
            </div>
        </div>
    </main>
</body>
```
```css
body {
    background-color: lightgray;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
    width: 100vw;
    font-size: 16px;
}
```

### Continued development

Need help in reducing the amount of css code i am using. I am not sure if all are really useful. I am always checking twice for unwanted piece of code.

### Useful resources

- [Font Awesome](https://fontawesome.com/) - This allowed me use the github logo with ease. 

## Author

- GitHub - [akil4](https://github.com/akil4)
- Frontend Mentor - [@akil4](https://www.frontendmentor.io/profile/akil4)
