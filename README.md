# Hints.css
It's a tooltip library based on the power of data-* attribute, pseudo elements, content property, CSS3 transforms and transitions in modern browsers

Author: Korben Carreno (http://www.korbencarreno.com)  
Version: 1.0 2013-10-09)   
Copyright 2013, Korben Carreno


## Instructions

#### 1. Download
Add [hints.css](https://github.com/KorbenC/Hints.css/blob/master/hints.css) to your project. The hints.css file is the only thing required.

### 2. Markup
Add the library to your HEAD tag like so.

```html
<link rel="stylesheet" href="hints.css"></link>
```

Any element on your page which needs to have a tooltip has to be given at least one of the position classes: hint--top, hint--bottom, hint--left, hint--right to position the tooltip.
```html
<p>Hello World, <span class="hint hint--top" data-hint="A simple hint."> hover over me!</span></p>
```
