### This is an  Timer deadline<h2>
        
_You **can** combine this with your web project_


```javascript
setClock('timer', deadline);
```
**setClock**: In this function, we write the id of our timer in the first argument, and secondly we pass our deadline,
which must be specified in the format (YYYY-MM-DD).
```html
<div class="timer-numbers" id="timer">...</div>
```
```javascript
let deadline = "your deadline";
```

here we associate our variables with our elements in html which are children classes of our timers
```javascript
        seconds = time.querySelector('.seconds'),
				minutes = time.querySelector('.minutes'),
				hours = time.querySelector('.hours'),
```
```html
<span class="hours"> </span>
					<span>:</span>
					<span class="minutes"> </span>
					<span>:</span>
					<span class="seconds"> </span>
```


*to use this feature just copy the code from the project and paste it into your project.*
