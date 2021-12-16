# snowflake
Random snowflake effect for webpage

[![Github](https://img.shields.io/badge/Github-1.0-blue.svg)](https://github.com/padhie/xmas)


## Install
Copy the js and css file in your project.

## Usage

### Using as Module
On this way you can use spawn the snowflakes in 3 js-lines.  
Even snowflake get random style-values.
```javascript
// import Module
import {Snow} from 'snow.js';

// init Modul with parent element and amount of snowflakes
const snow = new Snow(document.getElementById('snowflake-wrapper'), 100);

// spawn snowflakes
snow.spawn();
```

### Using without Javascript
This is a result to spawn snowflakes without any js-line.  
You can use this as base to implement your own solution in js/css or what ever you use.
```html
<!-- load snowflake style -->
<link rel="stylesheet" href="snow.css">

<!-- any wrapper element without style -->
<div>
    <!-- one element with random style-values -->
    <div class="snowflake" style="left: 42%; animation-delay: 2.2s, 4.1s;">❆</div>
    <div class="snowflake" style="left: 5%; animation-delay: 4.3s, 8.6s;">❆</div>
    <div class="snowflake" style="left: 55%; animation-delay: 9.9s, 7.4s;">❆</div>
    <div class="snowflake" style="left: 72%; animation-delay: 6.1s, 8.5s;">❆</div>
    <div class="snowflake" style="left: 96%; animation-delay: 7.1s, 7.4s;">❆</div>
    <div class="snowflake" style="left: 9%; animation-delay: 2.7s, 6.4s;">❆</div>
</div>
```

## Support
If you have an optimization feel free to add a Request.   
Please remember that everyone should use this easy without install any Framework, extern libraries or extensions.