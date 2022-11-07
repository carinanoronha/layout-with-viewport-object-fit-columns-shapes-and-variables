# CSS Layout Web 

A CSS website layout using viewport object; fit-columns; shapes and variables

## Viewport
* The viewport is the user's visible area of a web page.

* To determine the viewport size we can use the Chrome DevTools - Responsive Device Bar

```html  
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### Setting The Viewport
* [Google Developers - Viewport Meta Tag](https://web.dev/viewport/)

The ```content="width=device-width``` property instructs the page to match the screen's width.

The ```initial-scale``` property controls the zoom level when the page is first loaded.

* Without a viewport meta tag, mobile devices render pages at typical desktop screen widths, and then zoom out the page in order to fit the mobile screens.

## Responsive Font Size Units

#### CSS Viewport Units

#### CSS responsive units are units that are relative to the viewport size.

* ```vw```. - Viewport width. 1 vw equals 1% of the viewport width.
* ```vh``` - Viewport height. 1 vh equals 1% of the viewport height.

#### Relative unites - pixels, ems, rems

* ```px``` - specifies the height of the letters in CSS pixels

* ```em``` - Is relative to the element's parent font size.

* ```rem``` - is relative to the root (```<html>```) element's font size.

## Other Resources

- [Viewport](https://developer.mozilla.org/en-US/docs/Web/CSS/Viewport_concepts)

- [CSS Columns](https://developer.mozilla.org/en-US/docs/Web/CSS/columns)

- [CSS clip-path maker - Bennett Feely](https://bennettfeely.com/clippy/)

- [CSS Variables](https://www.w3schools.com/css/css3_variables.asp)
