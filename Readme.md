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



### Resources
- Clip Images: https://bennettfeely.com/clippy/
