# Daily

## 16.07.22

**Previously:** I learned about primitive data types and their methods i.e string methods, number methods and array methods. I also learn about booleans and boolean operators.

**Today:** I plan to learn about Date object

## 17.07.22

**Previously:** I learned about the Date object and Date get mehtods.

**Today:** I plan  on learning about conditionals and arrays

**Reflections**:

- I learned about conditionals, also called control flow. 
- I learned about if statements, the ternary operator and switch
- I learned about arrays being mutable and how they can store variable data types. They can also contain arrays.
-I learned about array methods like indexOf, splice, slice, includes, lastIndexOf, join, pop, push, shift, unshift and sort

## 23.07.22

**Previously**: I learned about arrays and conditionals.

**Today**: I plan on learning loops

**Reflections**:

## 02.08.22

**Previously**: I learned about loops. I encountered a problem while trying to write a function that returns a random ID based on the length the user wants it to be.

``` js

const generateRandomId = (numberOfChar) => {
  
	const characters = '1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz'
  let randomId = ''
	for (let i = 0; i < numberOfChar; i ++) {
    randomId += characters[Math.floor(Math.random() * 62) - 1]
  }
	console.log(randomId,randomId.length)
}


generateRandomId(10) 


// generateRandomId(20)

// generateRandomId(30)
```

The  above would sometimes return a randomId 8 characters longer. This was happening because the loop was sometimes returning undefined to randomId. I then updated it to look like this

``` js

const generateRandomId = (numberOfChar) => {
  
	const characters = '1234567890ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz'
  let randomId = ''
	for (let i = 0; i < numberOfChar; i ++) {
    randomId += characters[Math.floor(Math.random() * 62)]
  }
	console.log(randomId,randomId.length)
}


generateRandomId(10) 


// generateRandomId(20)

// generateRandomId(30)
```

**Today**: I plan to learn about DOM manipulation

**Reflections**: I learnt how to use js to target specific DOM elements. I learnt how to use querySelector, querySelectorAll, getElementById, classList.add, classList.toggle. I created a background gradient generator.


## 22.08.22

**Previously**: I learned about DOM manipulation

**Today**: I plan on covering the 9th part of Asabeneh's "30 Days Of JavaScript" challenge. The topic for today is "Higher Order Functions".

**Reflections**: Today, I learnt what higher order functions are. I also learnt to use methods like filter, every, reduce and some. I learned about explicit return arrow functions. I couldn't complete all the exercise from chapter 9.

## 23.08.22

**Previously**: I learnt about higher order functions, callbacks and some array methods. 

**Today**: I plan on completing yesterdays exercises.

**Reflections**: I finally completed the exercises with some help from my older brother.


## 30.08.22

**Previously**: I tackled some exercises from Asabeneh's "30 Days Of JavaScript" challenge.

**Today**: I plan on working on the 404-not-found page challenge by devchallenges.io.

**Reflections**: I've completed the 404 page challenge and it was awesome. Although the design I was to replicate wasn't complex, it feels good being able to bring a design to fruition.

