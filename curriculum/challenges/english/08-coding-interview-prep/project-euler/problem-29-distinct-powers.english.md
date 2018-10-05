---
id: 5900f3891000cf542c50fe9c
challengeType: 5
title: 'Problem 29: Distinct powers'
---

## Description
<section id='description'>
Consider all integer combinations of ab for 2 ≤ a ≤ 5 and 2 ≤ b ≤ 5:
22=4, 23=8, 24=16, 25=32
32=9, 33=27, 34=81, 35=243
42=16, 43=64, 44=256, 45=1024
52=25, 53=125, 54=625, 55=3125
If they are then placed in numerical order, with any repeats removed, we get the following sequence of 15 distinct terms:
4, 8, 9, 16, 25, 27, 32, 64, 81, 125, 243, 256, 625, 1024, 3125
How many distinct terms are in the sequence generated by ab for 2 ≤ a ≤ n and 2 ≤ b ≤ n?
</section>

## Instructions
<section id='instructions'>

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>distinctPowers(15)</code> should return 177.
    testString: 'assert.strictEqual(distinctPowers(15), 177, "<code>distinctPowers(15)</code> should return 177.");'
  - text: <code>distinctPowers(20)</code> should return 324.
    testString: 'assert.strictEqual(distinctPowers(20), 324, "<code>distinctPowers(20)</code> should return 324.");'
  - text: <code>distinctPowers(25)</code> should return 519.
    testString: 'assert.strictEqual(distinctPowers(25), 519, "<code>distinctPowers(25)</code> should return 519.");'
  - text: <code>distinctPowers(30)</code> should return 755.
    testString: 'assert.strictEqual(distinctPowers(30), 755, "<code>distinctPowers(30)</code> should return 755.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function distinctPowers(n) {
  // Good luck!
  return n;
}

distinctPowers(30);
```

</div>



</section>

## Solution
<section id='solution'>


```js
const distinctPowers = (n) => {
  let list = [];
  for (let a=2; a<=n; a++) {
    for (let b=2; b<=n; b++) {
      let term = Math.pow(a, b);
      if (list.indexOf(term)===-1) list.push(term);
    }
  }
  return list.length;
};
```

</section>