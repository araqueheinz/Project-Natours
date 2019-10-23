# NATOURS

## Summary
Natours is a website for a fictional company that offers tours in the Nature.

## Pillars of HTML & CSS

### **Responsive Design**
Responsive web design means that we build one website that works beautifully across all screen sizes on all devices. Responsive design is absolutely standard today. The fundamentals of responsive web design are:
- Fluid Layouts
- Media Queries
- Responsive Images
- Correct units
- Desktop-first vs Mobile-first

### **Maintainable and scalable code**
Writing maintainable and scalable code means:
- Clean Code
- Easy to understand
- Supports Future Growth
- Reusable
- How files are organized
- How to name classes
- How to structure HTML

### **Web performance**
Making a website or web app perform better means to make it faster and smaller in size, so that user has to download less data. Some things that we can do to make it perform better are:
- Less HTTP requests
- Less Code
- Compress code
- Use CSS preprocessor
- Less Images
- Compress images

## CSS behind the scenes
Starting point is when the browser start to **Load HTML** file. It takes the loaded HTML code and **Parse HTML**. It means that that it decodes the code line by line. The browser builds the **Document Object Model** or DOM, which describes the entire web document like a family three, with parents, children and siblings. This DOM is where the entire decoded html code is stored. As the browser parses the HTML it also finds the CSS stylesheet included in the HTML head and it starts **Loading CSS**. CSS is also parsed, but the parsing of CSS is more complex.

There are two steps when parsing the CSS. First, **Resolve conflicts CSS declarations(Cascade)**. Second, **Process final CSS values** for example: converting % values to pixels. Then the final CSS is also stored in a tree-like structure called **CSS Object Model** similar to DOM. Now that we have the HTML and CSS parsed and stored, these together form the **Render Tree**. To render the page the browser uses something called **The Visual Formatting Model** where it calculates and do some algorithms and then presents the **Final Rendered website**.

### Methodologies

There are plenty of methodologies out there aiming to reduce the CSS footprint, organize cooperation among programmers and maintain large CSS codebases. This is obvious in large projects like Twitter, Facebook and Github, but other projects often grow into some “Huge CSS file” state pretty quickly.

- OOCSS (Separating container and content with CSS “objects”)
- SMACSS (Style-guide to write your CSS with five categories for CSS rules)
- SUITCSS (Structured class names and meaningful hyphens)
- Atomic (Breaking down styles into atomic, or indivisible, pieces)

### BEM - Block Element Modifier
Is a nice and clean system for marking up our layouts. BEM is a naming styling that is created by Yandex (think of them as Russia's Google). BEM is trying to solve the naming problem and structure that CSS often run into. BEM also provides a better structure for your CSS code and scalable CSS.

- **Block**: Standalone entity that is meaningful on its own. Examples:
header, container, menu, checkbox, input
- **Element**: A part of a block that has no standalone meaning and is semantically tied to its block. Examples: menu item, list item, checkbox caption, header title
- **Modifier**: A flag on a block or element. Use them to change appearance or behavior. Examples: disabled, highlighted, checked, fixed, size big, color yellow

### 7-1 Pattern
The "7" refers to seven thematic directories. "1”: a single .scss file compiled into your site's CSS style sheet.
- base/
- components/
- layout/
- pages/
- themes/
- abstracts/
- vendors/

## Sass
Is a CSS preprocessor, an extension of CSS that adds power and elegance to the basic language.

### Compile Scss to CSS
- package.json
```
"scripts": {
    "compile:sass": "node-sass sass/main.scss css/style -w"
  },
```
- `-w` stands for watch, to compile every time we make a change in the scss file
- `npm run compile:sass`

### Automatic reload web browser
- `sudo npm i live-server -g`
- `live-server` in the main folder

## Dev Dependencies
- `npm i node-sass --save-dev`


### Resources
- Clip Images: https://bennettfeely.com/clippy/
- https://github.com/linea-io/Linea-Iconset
- https://unsplash.com/
- https://coverr.co/
