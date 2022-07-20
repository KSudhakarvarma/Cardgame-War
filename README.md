# Cardgame-War

This is a simple WARGAME created by using HTML, CSS & Javascript

They are certain rules to be followed while palying this Game.

Two players can play this game one is computer and another is player(YOU).

Created the fully functional game as a web application.

Releases: 

1: In this card game you are going to play ( WarGame ); and the rules of the game are given below.


2: The game is implemented by using container, divs in html file that will contain your cards and the buttons whuch will be trigger to draw cards. 
It is different from BlackJack / Rummy / Solitaire games.

3: Created a Javascript file that contains the Whole logic of the game.

4: Created a separate Javascript file that contains all of the functionality of selecting the deck, it is called as deck.js. This file can thus be reused in different games, by just changing the rules.


5: Added a function that takes in 2 arrays ( one for the suits, one for the values ) and combines them both into a fresh deck. Make it return a new "Card" for every element in the array, giving an array with 52 "Card"s. Calling  this function inside a new Deck data structure.

    (hint: you can combine two arrays into one with the flatmap() function. Conduct further research from the MDN docs to know more.)

6: created a function inside the deck to shuffle the array of "Cards" 
    (hint: you can use Math.random() inside the sort function.)

7: Inside the Card data structure, add a function that dynamically renders a new card from the array of "Card"s. Use this function in index.js to append the new card to your frontend.

    Now, deck.js provides us with a deck, a shuffle function and a function that allows us to withdraw a card.

8: We can also use these in index.js where we import deck.js and implement our game logic.

9: Built a function that, when triggered by a START button kickstarts the game and lays out the cards in your decided format.

10: Added buttons for drawing cards and an indicator that keeps track of the scores for both individuals.

11: Initialize a function that is triggered after every card draw and decides the winning and losing conditions.

<!-- 12: Created a modal that is triggered when the user wins or loses ( when the game completes ). You can display a trophy or meme of your choice based on the outcome. -->
