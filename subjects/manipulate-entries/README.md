## Manipulate Entries

### Instructions

Create 3 functions which work like the `.filter`, `.map` and `.reduce` array methods, but for the **entries** in the grocery cart.

- `filterEntries`: filters using both key and value.
- `mapEntries`: changes the key, the value or both.
- `reduceEntries`: reduces the entries.

Create 3 additional functions that use your previously created functions:

- `totalCalories`: that will return the total calories of a cart.
- `lowCarbs`: that leaves only those items which are lower than 50grams.
- `cartTotal`: that will give you the right amount of calories, proteins... and **all the other** items in your grocery cart.

> Think about the shape of `Object.entries()`

### Code provided

> The provided code will be added to your solution, and does not need to be submitted.

```js
// small database with nutrition facts, per 100 grams
// prettier-ignore
const nutritionDB = {
  tomato:  { calories: 18,  protein: 0.9,   carbs: 3.9,   sugar: 2.6, fiber: 1.2, fat: 0.2   },
  vinegar: { calories: 20,  protein: 0.04,  carbs: 0.6,   sugar: 0.4, fiber: 0,   fat: 0     },
  oil:     { calories: 48,  protein: 0,     carbs: 0,     sugar: 123, fiber: 0,   fat: 151   },
  onion:   { calories: 0,   protein: 1,     carbs: 9,     sugar: 0,   fiber: 0,   fat: 0     },
  garlic:  { calories: 149, protein: 6.4,   carbs: 33,    sugar: 1,   fiber: 2.1, fat: 0.5   },
  paprika: { calories: 282, protein: 14.14, carbs: 53.99, sugar: 1,   fiber: 0,   fat: 12.89 },
  sugar:   { calories: 387, protein: 0,     carbs: 100,   sugar: 100, fiber: 0,   fat: 0     },
  orange:  { calories: 49,  protein: 0.9,   carbs: 13,    sugar: 9,   fiber: 0.2, fat: 0.1   },
}
```

### Notions

- [filter](https://devdocs.io/javascript/global_objects/array/filter)
- [map](https://devdocs.io/javascript/global_objects/array/map)
- [reduce](https://devdocs.io/javascript/global_objects/array/reduce)
- [entries](https://devdocs.io/javascript/global_objects/object/entries)
- [fromentries](https://devdocs.io/javascript/global_objects/object/fromentries)
