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


## 31.08.22

**Previously**: I completed the 404 Not Found Responsive Web Developer challenge on [devchallenges.io](https://devchallenges.io/challenges/wBunSb7FPrIepJZAg0sY). 

**Today**: I plan on completing the My Team Page challenge on [devchallenges.io](https://devchallenges.io/challenges/hhmesazsqgKXrTkYkt0U). I'm trying to put to practice certain css techniques I have difficulty with i.e CSS grid.

**Reflections**: Css grid is still very confusing. I plan on watching some more courses on the topic and practice more by engaging in some challenges like devchallenges.io. It felt really nice hosting my own site online.

## 04.09.22

**Previously**: I completed the team page challenge on devChallenges. 

**Today**: I plan to complete the interior consultant page challenge.

**Reflections**: This challenge was somewhat annoying because I encountered some difficulties with stacking context and the width of some elements on certain screen sizes. It was frustrating because I had to inspect elements in the browser and tweak the styles from the inspector panel. Since I use the "Live Server" extension for Vscode, when it was time to add those tweaks to my styles.css the whole page would refresh making the other tweaks I haven't transfered to my stylesheet disappear making me start all over again trying different properties to fix the problem. Other than the above, it was a nice experience.

## 17.09.22

**Previously**: I've been working on my portfolio site for a while now and I've encountered some problems trying to make the site responsive. One problem that kept bugging me was that when a user opened the hamburger menu on a small device and rotates his screen, if the width of the screen width is 768px or higher, the hamburger menu disappears and becomes a normal navbar but still keeps the active hamburger styles.

**Reflections**: The problem with the navbar was as a result of me using the wrong media query. I used the min-width property instead of max-width.

## 22.10.22

**Previously**: I solved all the problems I encountered with my portfolio site navbar. I also started creating an unbeatable tic-tac-toe ai. I encountered small challenges here and there which I was able to solve after watching a couple of YouTube videos. A major block I experienced was not being able to understand the Minimax algorithm.

**Today**: I plan on watching some YouTube lectures on the Minimax algorithm.

**Reflections**:

## 28.10.22 

**Previously**: I struggled with implementing the Minimax algorithm for my unbeatable tictactoe game. After going through Youtube for a while I came across this - [The Coding Train](https://youtu.be/trKjYdBASyQ). With the knowledge I gathered from articles I read, I was finally understood the algortithm. The Minimax algorithm is a recursive function that returns a score based on the terminal state of the game i.e if X wins it returns +10 (maximizer), if O wins it returns -10 (minimizer) and if it's a tie, it returns 0. The algorithm loops through all the possible spots a player can play in and then returns the score. If the current state is not terminal, it calls itself again and goes through this cycle until it gets to a terminal state.

**Today**: I plan on learning SASS. I'm using a youtube playlist i found by [The Net Ninja](https://youtube.com/playlist?list=PL4cUxeGkcC9iEwigam3gTjU_7IA3W2WZA).
