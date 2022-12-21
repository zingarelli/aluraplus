# Alura+ (Alura Plus)

[Veja esta página em português](#detalhes-do-projeto)

Development of the landing page of Alura+ website (which is in Portuguese), based on the design created and [provided in a Figma file](https://www.figma.com/file/tFDVyNuKhrT2G03k2dCstW/Alura-Plus---Layout?node-id=0%3A1). 

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Página inicial da Alura+**
| :label: Tecnologias | HTML, CSS
| :rocket: URL         | https://zingarelli.github.io/aluraplus/
| :fire: Course     | https://www.alura.com.br/curso-online-html-css-praticando-html-css

![](https://user-images.githubusercontent.com/19349339/189158902-3dd85fd0-dedc-4358-bdc9-124acbd8a96f.png#vitrinedev)

## Credits

This project was developed in a course from [Alura](https://www.alura.com.br) called "HTML e CSS: praticando HTML/CSS" (HTML and CSS: Practicing with HTML/CSS), as a way of consolidating all the knowledge acquired in the HTML/CSS Specialization. 

Instructor: [Mônica Mazzochi Hillman](https://github.com/MonicaHillman)

## What we learned
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

## Additional feature: responsiveness
As an additional feature, I added specific styles for medium (up to 940px) and small (up to 425px) screens, using media queries.

**Desktop view**

![gif of the page on larger screens](https://user-images.githubusercontent.com/19349339/208908562-74c34e26-e97d-4221-a013-610688e03472.gif)

**Mobile view**

![gif of the page on mobile screens](https://user-images.githubusercontent.com/19349339/208908552-81297873-a4e5-4359-86d7-50f87a8d83c7.gif)

---

## Detalhes do projeto

Desenvolvimento da página inicial da Alura+ (um site de divulgação de um plano que combina a Alura com o Alura Língua), baseado no design disponibilizado em um [arquivo Figma](https://www.figma.com/file/tFDVyNuKhrT2G03k2dCstW/Alura-Plus---Layout?node-id=0%3A1). 

## Créditos

Este projeto foi desenvolvido em um curso da [Alura](https://www.alura.com.br) chamado "HTML e CSS: praticando HTML/CSS", e foi uma forma de consolidar todos os conhecimentos aprendidos na formação de HTML/CSS. 

**Instrutora:** [Mônica Mazzochi Hillman](https://github.com/MonicaHillman)

## O que aprendemos

A partir do arquivo Figma, nós identificamos seções e elementos semelhantes, o que nos ajudou a estruturar o HTML e o CSS para um melhor reúso de classes, estilos e padrões. Com isso, também ficou mais claro identificar onde aplicar o Flexbox e o Grid.

As classes nos elementos HTML foram nomeadas utilizando a [metodologia BEM](http://getbem.com/introduction/) (Block-Element-Modifier, ou Bloco-Elemento-Modificador), que é uma maneira bem legal de tornar as classes fáceis de serem encontradas, bem organizadas e evitar conflitos de nomes repetidos. Por exemplo:

```html
<section class="container principal">
        <div class="container__box">
            <h1 class="container__titulo">
```

Nós definimos variáveis no arquivo CSS para as cores e fontes utilizadas no site, prevenindo a repetição de código e favorecendo seu reúso e manutenção. Quando é necessária uma mudança em uma cor ou fonte, precisamos somente modificar estas variáveis, ao invés de procurar no código todo onde elas foram aplicadas. Segue um exemplo:

```css
:root {
    --principal-branco: #FFFFFF;
    --secundario-cinza: #C0C0C0;
    --background-escuro: #00030C;
    --botao-azul: #167BF7;
    --botao-azul-efeito: #045AC4;
    --principal-fonte: 'Inter';
}

body {
    color: var(--principal-branco);
    background-color: var(--background-escuro);
    font-family: var(--principal-fonte), sans-serif;
    font-size: 16px;
    font-weight: 400px;
}
```

## Funcionalidade adicional: responsividade

Como funcionalidade adicional, eu adicionei estilos específicos para telas de tamanho médio (até 940px) e pequeno (até 425px), utilizando "media queries".

**Tela de computador**

![gif da página vista em telas grandes](https://user-images.githubusercontent.com/19349339/208908562-74c34e26-e97d-4221-a013-610688e03472.gif)

**Tela de celular**

![gif da página vista em telas de celular](https://user-images.githubusercontent.com/19349339/208908552-81297873-a4e5-4359-86d7-50f87a8d83c7.gif)
