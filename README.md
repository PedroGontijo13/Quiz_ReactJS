# Quiz_ReactJS

Challenge 1:
Given an array of numbers, return an array of each number, squared


```js
const nums = [1, 2, 3, 4, 5]
// -->       [1, 4, 9, 16, 25]
// Your code here
const array1 = [1, 2, 3, 4, 5]

// Pass a function to map

const map1 = array1.map(x => x ** 2);

console.log(map1);
```

Challenge 2:
Given an array of strings, return an array where the first letter of each string is capitalized

```js
const names = ["alice", "bob", "charlie", "danielle"]
// -->        ["Alice", "Bob", "Charlie", "Danielle"]
// Your code here
const array1 = ["alice", "bob", "charlie", "danielle"];

// Pass a function to map
const map1 = array1.map(function(str) {
    return str.charAt(0).toUpperCase() + str.slice(1);
  });

console.log(map1);
```




Challenge 3:
Given an array of strings, return an array of strings that wraps each of the original strings in an HTML-like `<p></p>` tag.


```js
E.g. given: ["Bulbasaur", "Charmander", "Squirtle"]
return: ["<p>Bulbasaur</p>", "<p>Charmander</p>", "<p>Squirtle</p>"]
const pokemon = ["Bulbasaur", "Charmander", "Squirtle"]
// -->          ["<p>Bulbasaur</p>", "<p>Charmander</p>", "<p>Squirtle</p>"]
// 

const pokemonElements = pokemon.map(function(name) {
  return <p>{name}</p>;
});
```


Challenge 4:

1. What does the `.map()` array method do?


```md
The map array method loops through our array and returns it with some change. For exemple:

const map1 = array1.map(x => x + 1); -> We return the element incresed by 1
```

2. What do we usually use `.map()` for in React?

```md
// Your answer here
We usually use the method to return the element with one HTML tag. For example: 

const pokemonElements = pokemon.map(function(name) {
  return <p>{name}</p>;
});
```

3. Why is using `.map()` better than just creating the components
   manually by typing them out?

```md
// Your answer here
Its better because we will not need to write a lot of lines of code and makes the code more readable and easier to understand.
```
