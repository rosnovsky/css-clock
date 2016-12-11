# Simple Analog CSS clock

This simple CSS Clock project was inspired by @wesbos and his [#Javascript30](http://javascript30.com) challenge.

## My favorite features

Moving rotation origin along the element:

```css
transform-origin: 100%;
```

Cool ```cubic-bezier``` transition effect for nice second hand jolting:

```css
transition: all 0.05s;
transition-timing-function: cubic-bezier(0.1, 2.7, 0.6, 1);
```

Adding simple styles via JS "move" hands around:

```javascript
secondHand.style.transform = `rotate(${secondsDegrees}deg)`;
```

# [See in action](https://rosnovsky.github.io/css-clock/)
