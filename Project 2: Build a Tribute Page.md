
## Project 2
 html
```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Tribute Page</title>
    <link rel="stylesheet" href="styles.css">
  </head>
  <body>
    <main id="main">
      <h1 id="title">Dr. Norman Borlaug</h1>
      <div id="img-div">
        <img id="image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute-page-main-image.jpg">
        <figcaption id="img-caption">Dr. Norman Borlaug, the father of the Green Revolution, stands in front of a field of wheat.</figcaption>
      </div>
      <p id="tribute-info">Dr. Norman Borlaug was an American agricultural scientist who is considered the father of the Green Revolution. He developed high-yielding varieties of wheat that helped to combat famine in developing countries and is credited with saving over a billion lives.
      </p>
      <a id="tribute-link" href="https://en.wikipedia.org/wiki/Norman_Borlaug" target="_blank">Learn more</a>
    </main>
  </body>
</html>
```

css
```css
#main {
  width: 80%;
  margin: 0 auto;
  text-align: center;
}

#img-div {
  display: block;
  margin: 0 auto;
  text-align: center;
}

#image {
  max-width: 100%;
  height: auto;
  display: block;
  margin: 0 auto;
}
