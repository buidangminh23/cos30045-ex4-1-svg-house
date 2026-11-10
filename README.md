# Exercise 4.1: Draw SVGs

COS30045 Data Visualisation, Bui Dang Minh (105716425)

Live page: https://buidangminh23.github.io/cos30045-ex4-1-svg-house/

A house and garden drawn with every SVG shape (rect, circle, ellipse, line, polyline, polygon, path and text). The two windows are grouped in a `g` element positioned with `transform="translate(170, 225)"`. The page includes an annotated screenshot that matches the coordinates in the code to the picture, and a description of the SVG in the DOM.

## Files

- `index.html` - the page and the inline SVG
- `css/style.css` - page styles
- `images/annotated-house.png` - annotated coordinate screenshot
- `images/dom-devtools.png` - screenshot of the SVG in the DOM (developer tools, Elements panel)

## Run locally

Open the folder in VS Code and start Live Server, or run `python -m http.server` in the folder and open http://localhost:8000. The page must be served by a server so that `d3.csv` can load the data files.
