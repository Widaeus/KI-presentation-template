# KI presentation template
This repository provides a template for presentations featuring the logo of the Karolinska Institute, Department of Clinical Sciences, Danderyd Hospital. The presentations are generated as Reveal.js slides using Quarto.

To create your presentation, edit the index.qmd file. Quarto will generate the index.html file, which is the final presentation. This file can be hosted on a web server or viewed locally in any web browser.
## Dependencies
- Quarto (for generating the presentation from .qmd to .html)
- Node.js and npm (for managing development dependencies)
- Reveal.js (presentation framework)
- Gulp (for automating tasks like minifying, serving locally, etc.)
- Rollup (for bundling and optimizing JavaScript)
- Babel (for transpiling JavaScript)
- Sass (for compiling stylesheets)
- Fitty (for dynamic text resizing)
- Highlight.js (for code syntax highlighting)
- Marked (for Markdown parsing)

## Instructions

1. 
To get started, clone the repository to your local machine:
```bash
git clone https://github.com/Widaeus/KI-presentation-template
```

2. 
Make sure you have Node.js installed. Then, run:
```bash
npm install
```

3. 
Run Gulp for development: To start the local development server and build the project, run:
```bash
gulp
```

4. 
Build the presentation: If you want to manually build the project, use Rollup or Quarto depending on what you're targeting:
```bash
quarto render index.qmd
```
