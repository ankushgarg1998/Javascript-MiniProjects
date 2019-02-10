# Javascript-MiniProjects


## Drum Kit 🥁
🎵 [Try it !](https://ankushgarg1998.github.io/Javascript-MiniProjects/Drum%20Kit/)

![Drum Kit Image](https://github.com/ankushgarg1998/Javascript-MiniProjects/blob/master/Drum%20Kit/Screen.png "Drum")

#### HTML
```html
data-* attribute
<div data-key="x">
<audio data-key="x" src=""></audio>
```

#### CSS
```CSS
{
align-items: center;
justify-content: center;
transition: all 0.5s ease;
text-shadow: 0 0 0.5rem black;
}

.playing {
  transform: scale(1.5);
  border-color: #ffc600;
  box-shadow: 0 0 1rem #ffc600;
}
```
#### JS
```javascript
audio.currentTime = 0;
audio.play();
key.classList.add('playing');
window.addEventListener('keydown', function);
forEach loop
```

## CSS Clock 🕐
:clock3: [Try it !](https://ankushgarg1998.github.io/Javascript-MiniProjects/Clock/)

![Clock Image](https://github.com/ankushgarg1998/Javascript-MiniProjects/blob/master/Clock/Screen.png "Clock")

#### CSS
```CSS
{
transform-origin: 100%;
transform: translateY(-3px);
transform: rotate(90deg);
transition: all 0.5s;
transition-timing-function: cubic-bezier();
}
```

#### JS
```javascript
- Date()
  - getSeconds()
  - getMinutes()
  - getHours()

- [element].style.transform = 'rotate(20deg)';
- setInterval(function, miliseconds)
```

## CSS Variables Updating with JS
📓 [Try it !](https://ankushgarg1998.github.io/Javascript-MiniProjects/CSS%20Variables/)

![CSS Variables](https://github.com/ankushgarg1998/Javascript-MiniProjects/blob/master/CSS%20Variables/Screen.png "CSS Variables")

- The difference between Sass variables and CSS variables is that Sass variables cannot be changed once compiled. But CSS Variables can be dynamically updated.

#### CSS
```CSS
:root {
  --blur: 10px;
}
```

#### JS
```javascript
document.documentElement.style.setProperty(`--blur`, 20px);
```

## Array Cardio
- filter()
- map()
- sort()
- reduce()

## Flex Panels