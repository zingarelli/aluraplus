# Alura+ (Alura Plus)

Development of the landing page of Alura+ website (which is in Portuguese), based on the design created and [provided in a Figma file](https://www.figma.com/file/tFDVyNuKhrT2G03k2dCstW/Alura-Plus---Layout?node-id=0%3A1). 

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Alura Plus**
| :label: Tecnologias | HTML, CSS
| :rocket: URL         | https://zingarelli.github.io/aluraplus/
| :fire: Desafio     | 


![](https://user-images.githubusercontent.com/19349339/189158902-3dd85fd0-dedc-4358-bdc9-124acbd8a96f.png#vitrinedev)

## Project details

### Credits

This project was developed in a course from [Alura](https://www.alura.com.br) called "HTML e CSS: praticando HTML/CSS" (HTML and CSS: Practicing with HTML/CSS), as a way of consolidating all the knowledge acquired in the HTML/CSS Specialization. 

Instructor: [Mônica Mazzochi Hillman](https://github.com/MonicaHillman)

### What we learned
From the Figma file, we identified similar sections and elements, which helped us structure HTML and CSS files for a better reuse of classes, styles and patterns. With that, it was also easier to identify where to apply Flexbox and Grid.

Classes in the HTML file were named using [BEM methodology](http://getbem.com/introduction/) (Block-Element-Modifier), which is a nice way of keeping classes easy to find, well organized and avoiding conflicts between classes with similar names. For example:

```html
<section class="container main">
        <div class="container__box">
            <h1 class="container__title">
```

We defined variables in the CSS file for colors and font used in the website, preventing repetition and favouring reuse and maintenance of our code. Whenever a change in color or font needs to be applied, we only modify these variables. Here's an example:

```css
:root {
    --main-white: #FFFFFF;
    --secondary-grey: #C0C0C0;
    --bg-dark: #00030C;
    --button-blue: #167BF7;
    --button-blue-effect: #045AC4;
    --main-font: 'Inter';
}

body {
    color: var(--main-white);
    background-color: var(--bg-dark);
    font-family: var(--main-font), sans-serif;
    font-size: 16px;
    font-weight: 400px;
}

```

### Additional feature: responsiveness
As an additional feature, I added specific styles for medium (up to 940px) and small (up to 425px) screens, using media queries.
