### Hazel and Hamsika's Mini NEA

# Mini NEA: SpellCast

## Analysis 

##### The problem: 

People need entertainment. While there are many games avaliable, few are multiplayer. It can be difficult to connect with friends across long distances regularly. So we are developing a game that is short, snappy but interesting. This should make it easy to connect repeatedly and build a relationship with friends. 

##### Stakeholders: 

Our stakeholders are going to be everyone who enjoys playing online games and we will be testing our product between a few iterations to get feedback throughout the process. In particular, we will be testing the demographic of school students as we believe the group most impacted, as well as family and friends from Australia and India. 

##### Research: 

The game we have taken inspiration from is Divineko: Magic Cat, it has an interesting concept of drawing spells to cast them. However, we think the layout of the game is not compatible with multiplayer, so we abstracted it. We also took inspiration from mastermind the boardgame, where you crack codes.  

##### Features:

We plan to include ai, to pick up on visual cues like hands forming the symbols for the game. A key feature of our game is to include multiplayer through the browser using web-sockets. Another is to have a visual representation of the current state of the game drawn to a canvas. 

## Design

##### Structure:

The ai aspect will be using teachable machine, training and downloading a model. We will have the machine recognise hand symbols and if the certainty of symbol is high enough, e.g >0.9, this will be the 'element'. This will be drawn to the canvas, confirmed by the user and then used as a guess to the code. This should all be written in javascript with a html canvas. (Websockets Hamsika)