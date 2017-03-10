# animationCounter.js
animationCounter.js is a jQuery plugin that animates a number from a value to another or to infinite value <br>

# 1. Download & Installation
##### 1.1. Download the latest version from [GitHub](https://github.com/mpavade/animationCounter.js/archive/master.zip)<br>

##### 1.2 or install via bower package manager:<br>
```
bower install animationCounter.js
```

##### 1.3 Add your js file 'animationCounter.js' after jQuery, before your closing body tag   <br>
```html
<script src="animationCounter.js" type="text/javascript">
```

# 2. Use

In your JS file, call the animationCounter() function with default parameters<br>
```javascript
$('yourdiv').animationCounter();
```

Or call animationCounter() function with your parameters like this the following example : <br>
```javascript
$('#yourdiv').animationCounter({
start: 0,
end: 500,
step: 1,
delay: 1000,
txt: ' €'
});
```

# 3. Options

| Parameters | Type | Definition | Default |
| ------ | ------ | ------ | ------ |
| `start` | integer | The value where the counter started | 0 |
| `end` | integer | The value where the counter stopped | null |
| `step` | integer | The interval between the values | 1 |
| `delay` | integer | The intervals (in milliseconds) on how often to execute the code | 1000 |
| `txt` | string | The text displayed after your counter | '' |


# 4. Demo

You can see how it's works on the <a href="https://mpavade.github.io/animationCounter.js/example/">demo</a> page


# 5. License

Copyright © Micheline Pavadé<br>
This project is released under the [MIT License](LICENSE).
