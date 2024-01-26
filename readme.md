# Crea tu curriculum usando HTML y CSS

## Instrucciones

Usando solamente HTML y CSS crea tu curriculum vitae.

## Proyecto en 4geeks

https://4geeks.com/interactive-coding-tutorial/build-your-resume-html-css

## Recursos

### Documentaciones

- [Documentacion HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Documentacion CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [Documentacion CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)

#### Youtube

- [Canal 4geeks](https://www.youtube.com/c/4GeeksAcademy)
- [CSS Kevin Powel](https://www.youtube.com/@KevinPowell/featured)

### Tipografías

- [Google Fonts](https://fonts.google.com/)

Las tipografías que se usan en el proyecto son:

- Roboto (Proyecto 2)

```css
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap");
```

- Inconsolata (Proyecto 1)

```css
@import url("https://fonts.googleapis.com/css2?family=Inconsolata:wght@200..900&display=swap");
```

### Colores

- [Coolors](https://coolors.co/)

Los colores que se usan en el proyecto son:

Proyecto 1:

- Color de fondo: #fffcf9

- Color de acento: #ff6b6b

Proyecto 2:

- Color de fondo: #29638a

- Color de acento: #fafafa

## Convenciones de nombrado

- [BEM](http://getbem.com/naming/)

BEM(Block, Element, Modifier) es una metodología de nombrado para clases de CSS. Es una convención de nombrado que nos ayuda a escribir CSS mantenible y escalable.

```css
/* Block component */
.card {
  border-radius: 3px;
  background-color: #ffffff;
  padding: 20px;
}

/* Element that depends upon the block */
.card__header {
  font-size: 18px;
}

/* Modifier that changes the style of the block */
.card--rounded {
  border-radius: 10px;
}
```
