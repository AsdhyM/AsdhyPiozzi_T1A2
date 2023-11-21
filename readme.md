# Portfolio

## Overview
This is a portfolio website to demonstrate the skills acquired during the first three weeks of Coder Academy booth camp. This is a work in process and will add features in readme that I implement in website.

## Componenets

### Header
Header is located at the first part of the website, within it are the logo, name and the following navigation bars:

    * Home
    * About
    * Contact

Code for the header:

```html
<header>
    <div class="logo-name">
        <a href="./index.html">
            <img src="logo.png" alt="Logo Image">
        </a>
        <p class="name">
            <span class="asdhypiozzi-text">Asdhy Piozzi</span>
        </p>
    </div>

    <nav id="nav-items">
        <a href="./index.html">Home</a>
        <a href="./pages/about.html">About</a>
        <a href="./pages/contact.html">Contact</a>
    </nav>
</header>
```

### Footer
Footer is at the end of the page and contains links for social media and contact information.
The code it's as follows:
```html
<footer>
    <div class="social-media">
        <a href="https://www.facebook.com" target="_blank">
            <i class="fa-brands fa-facebook"></i>
        </a>
        <a href="https://www.instagram.com" target="_blank">
            <i class="fa-brands fa-instagram"></i>
        </a>
        <a href="https://www.github.com" target="_blank">
            <i class="fa-brands fa-github"></i>
        </a>
        <a href="https://www.linkedin.com" target="_blank">
            <i class="fa-brands fa-linkedin"></i>
        </a>
    </div>
    <div class="info">
        <b><p>Contact: 0404111222</p></b>
        <b><a href="mailto: Email">asdhypiozzi@fakeemail.com</a></b>
    </div>
</footer>
```


