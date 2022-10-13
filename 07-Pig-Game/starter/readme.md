<h1 align="center">Pig Game</h1>

  <p align="center">
    <a href="https://pig-game-angi.netlify.app/"><strong>:point_right: Live Demo Here :point_left:</strong></a>
    <br />
    <br />
  </p>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#intro">Intro</a>
      <ul>
        <li><a href="#rules">Rules</a></li>
      </ul>
    </li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-using">Built Using</a></li>
      </ul>
    </li>
    <li><a href="#contact-me">Contact</a></li>
  </ol>
</details>

<!-- Intro -->
## Intro

https://user-images.githubusercontent.com/43470248/193452263-f9a35f60-1618-4977-86c5-bbe1352f0bf5.mp4

### Rules
&emsp; On a turn, a player rolls the die 🎲 repeatedly. The goal is to accumulate as many points as possible, adding up (__Hold__) the numbers rolled on the die 🎲. However, if a player rolls a 1, the player's turn is over and any points they have accumulated during this turn are forfeited. Rolling a 1 doesn't wipe out your entire score from previous turns, just the total earned during that particular roll.
<br /> &emsp; A player has to choose to hold (stop rolling the die 🎲) if they do not want to take a chance of rolling a 1 and losing all of their points from this turn. If the player chooses to hold, all of the points rolled during that turn are added to his or her score.
<br /> &emsp; When a player reaches a total of 100 points, that player is declared the winner and the game ends.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ABOUT THE PROJECT -->
## About The Project

![Pig-Game-Flowchart](https://github.com/darirak/complete-javascript-course/blob/master/07-Pig-Game/starter/pig-game-flowchart.png?raw=true)

### **Flowchart of the Project**
* ![#dfc686](https://via.placeholder.com/15/dfc686/dfc686.png) Yellow - The possible actions a user can take
* ![#94bb80](https://via.placeholder.com/15/94bb80/94bb80.png) Green - Shows what happens as soon as one action is executed
* ![#8ba6ce](https://via.placeholder.com/15/8ba6ce/8ba6ce.png) Blue - `If-Else` where we check for a certain condition
* ![#c58280](https://via.placeholder.com/15/c58280/c58280.png) Red - Finish Line :)

### Summary

* **First Player to Reach 100 Points Wins the Game**

  * Use `Roll Dice` to get a value from 1 to 6
  * The values from 2 to 6 gets added in the `Current` block and you can roll the dice again
  * Using the `Hold` button will add the `Current` score to your `Total Score`, preventing resets from 1 rolls
  * If you roll 1 on the dice, you lose all of your `Current` points and ends your turn
  * You can use `New Game` to reset the game instead of refreshing your page :) 


### Built Using

* [![HTML][HTML.com]][HTML-url]
* [![CSS][CSS3.com]][CSS-url]
* [![JavaScript][JavaScript.com]][JavaScript-url]
* [![DOM-Manipulation][DOM.com]][DOM-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact Me

<p>
<div align="center">
  <a href="https://darirak.ro/"><img src="https://img.shields.io/badge/-My%20Portfolio%20Website-blueviolet?style=for-the-badge" alt="Alcaan Design - My Portfolio Website" /></a>
  <a href="https://www.linkedin.com/in/darirak/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>

[HTML.com]: https://img.shields.io/badge/html-e44d26?style=for-the-badge&logo=html5&logoColor=white
[HTML-url]: https://www.html.com/
[CSS3.com]: https://img.shields.io/badge/css-0070ba?style=for-the-badge&logo=css3&logoColor=white
[CSS-url]: https://www.css3.com/
[JavaScript.com]: https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
[JavaScript-url]: https://www.javascript.com/
[DOM.com]: https://img.shields.io/badge/dom_manipulation-ae780e?style=for-the-badge
[DOM-url]: https://www.freecodecamp.org/news/javascript-dom-manipulation/
