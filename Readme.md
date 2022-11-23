# The Rules of JSX 
## 1. Return a single root element
> To return multiple elements from a component, wrap them with a single parent tag.For example, you can use a > > <div>:If you don’t want to add an extra <div> to your markup, you can write <> and </> instead:
## 2. Close all the tags 
> JSX requires tags to be explicitly closed: self-closing tags like <img> must become <img />, and wrapping tags like <li>oranges must be written as <li>oranges</li>.
## 3. camelCase all most of the things! 
> This is why, in React, many HTML and SVG attributes are written in camelCase. For example, instead of stroke-width you use strokeWidth.