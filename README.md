<p align="center">
  <img src='https://raw.githubusercontent.com/oma-shop/corporate-identity/master/CI-dark.png' border='0' width='1000' alt='logo-outline-light'/>
  <img src='https://raw.githubusercontent.com/oma-shop/corporate-identity/master/CI-light.png' border='0' width='1000' alt='logo-outline-light'/>
</p>

# Corporate Identity
Here we manage the most important assets for the OMG (Open Marketplace Applications) Project.

## Font
We use Open Sans as a font. You can download the the whole font from fonts.google.com or just use the one from here. We are only using two font-weight's, ```400``` for paragraphs and ```800``` for headings. You can just copy the styles from below to get started.

```CSS
@import url('https://fonts.googleapis.com/css?family=Open+Sans:400,800&display=swap');

* {
  font-family: 'Open Sans', sans-serif;
}

span, p, blockquote, ul, ol, {
  font-weight: 400;
}

h1, h2, h3, h4, h5, h6, a, button {
  font-weight: 800;
}

```

## Colors
You can get the HEX and RGB colors from here.

```CSS
/* HEX */
:root {
  --primary: #4CB6C2;
  --primary_light: #7FC7BD;
  --white: #FFFFFF;
  --light: #EDF7F2;
  --dark: #193F43;
  --black: #0F282B;
}

/* RGBA */
:root {
  --primary: rgb(76,182,194);
  --primary_light: rgb(127,199,189);
  --white: rgb(255,255,255);
  --light: rgb(237,247,242);
  --dark: rgb(25,63,67);
  --black: rgb(15,40,43);
}
```

## Logo
In the logo folder you can find the logo itself as well as only the symbol. You can get both as ```.jpg```, ```.png```, ```.svg```, ```.pdf``` or as original file ```.ai```.

## Adobe XD File
Here you can find the Corporate Identity XD File as well as the Mockups for the Mobile Application.