# --Description-- Build a Tribute Page

**User Stories:**

1. Your tribute page should have a `main` element with a corresponding `id` of `main`, which contains all other elements
1. You should see an element with an `id` of `title`, which contains a string (i.e. text), that describes the subject of the tribute page (e.g. "Dr. Norman Borlaug")
1. You should see either a `figure` or a `div` element with an `id` of `img-div`
1. Within the `#img-div` element, you should see an `img` element with a corresponding `id="image"`
1. Within the `#img-div` element, you should see an element with a corresponding `id="img-caption"` that contains textual content describing the image shown in `#img-div`
1. You should see an element with a corresponding `id="tribute-info"`, which contains textual content describing the subject of the tribute page
1. You should see an `a` element with a corresponding `id="tribute-link"`, which links to an outside site, that contains additional information about the subject of the tribute page. HINT: You must give your element an attribute of `target` and set it to `_blank` in order for your link to open in a new tab
1. Your `#image` should use `max-width` and `height` properties to resize responsively, relative to the width of its parent element, without exceeding its original size
1. Your `img` element should be centered within its parent element

## --solutions--

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
