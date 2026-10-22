# Exercise 4.1: Draw SVGs

COS30045 Data Visualisation, Bui Dang Minh (105716425)

Live page: https://buidangminh23.github.io/cos30045-ex4-1-svg-house/

A house and garden drawn with every SVG shape (rect, circle, ellipse, line, polyline, polygon, path and text). The two windows are grouped in a `g` element positioned with `transform="translate(170, 225)"`. The page includes an annotated screenshot that matches the coordinates in the code to the picture, and a description of the SVG in the DOM.

## Files

- `index.html` - the page and the inline SVG
- `css/style.css` - page styles
- `images/annotated-house.png` - annotated coordinate screenshot

## Run locally

Open the folder in VS Code and start Live Server, or run `python -m http.server` in the folder and open http://localhost:8000. The page must be served by a server so that `d3.csv` can load the data files.

## Generative AI Reflection

- **Tool:** Claude Opus 5.5 (Anthropic), used through Claude Code in October 2026.
- **What I used it for:** drafting the HTML, CSS and D3 code by following the steps of the exercise brief, and explaining what each D3 method does.
- **What I changed or checked:** I ran the page with a local server, checked the data in the browser console and the elements in the DOM, and checked that the code only uses techniques from the Week 4 to Week 6 lectures and exercises.
- **What I learned:** how the SVG coordinate system works (origin at the top left, y going down) and how a group shares styles and a transform between its children.
- **Limitations:** the AI wrote code faster than I could read it, so I went through every file line by line before the demonstration. Each commit that contains generated code says so in the commit message, and each code file starts with a comment marking the GenAI use.
