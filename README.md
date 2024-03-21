#### INNRAN532_BCL2401_GroupB_InnocentRangaka_JSL04

# JSL04 Submission: Monster Ternary Operator

This repository demonstrates the use of the ternary operator in JavaScript to solve various challenges related to Monster Energy drinks.

## My Solutions

### Challenge 1: Flavor Selection

This effectively uses the ternary operator to determine and print the user's Monster Energy drink preference between regular and Sugar-free.

```javascript
let userPreference = 'Sugar-free';

console.log(`${userPreference === 'Sugar-free' ? 'Sugar-free' : 'Regular'}`);
```

### Challenge 2: Stock Check

This uses ternary operator to effectively determine the appropriate stock status based on the number of cans left (less or more than 5 cans) and prints the appropriate status message that it is the time to restock or we're stocked.

```javascript
let cansLeft = 3;

console.log(`${cansLeft < 5 ? "Time to restock!" : "We're stocked!"}`);
```

### Challenge 3: Workout Intensity

This uses the ternary operator to determine if the user needs a Monster Energy drink to boost their workout based on their heart rate and prints the appropriate advice that the boost is needed or energy levels are high.

```javascript
let heartRate = 95;

console.log(`${heartRate < 100 ? 'Boost needed!' : 'Energy levels are high!'}`);
```

### Challenge 4: Temperature Suitability

This uses the ternary operator to determine the Monster Energy drink temperature suitability and prints the indicating message that the drink is perfectly chilled or need further chilling.

```javascript
let currentTemp = 4;

console.log(`${currentTemp <= 5 ? 'Chilled to perfection!' : 'Needs a cooler!'}`);
```

### Challenge 5: Late Night Coding Session

This uses the ternary operator to determine if it's a good time for a Monster Energy drink based on the current hour between 7am and midnight using 24-hour format,and suggests if it is okay to have a Monster Energy drink or drinking water is a better choice.

```javascript
let currentHour = 22;

console.log(`${currentHour >= 7 && currentHour < 24 ? 'Unleash the beast!' : 'Better stick to water.'}`);
```