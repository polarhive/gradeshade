# Grade Shade

> What Colour is your GPA? 🥸

## Colour Generation

## Mapping

```js
S->F
F->0
A,B,C,D,E
```

Then, simply concat!

### Credit-Weighted

```javascript
const weightedGrade = totalPoints / totalCredits;
const red = Math.max(0, 255 - (weightedGrade * 25));
const green = Math.max(0, weightedGrade * 25);
const blue = 128; // blue

const weightedHex = `#${Math.floor(red).toString(16).padStart(2, '0')}${Math.floor(green).toString(16).padStart(2, '0')}${Math.floor(blue).toString(16).padStart(2, '0')}`;
```

---

for fun and giggles <3
