# Drum Machine

## Introduction
A drum pad that can be used by clicking individual pads or by pressing the appropriate keys.

This project is part of freeCodeCamps Frontend Libraries certificate.

***

## Project Requirements
* There is an outer container with a corresponding id="drum-machine" that contains all other elements.
* Within #drum-machine I can see an element with a corresponding id="display".
* Within #drum-machine I can see 9 clickable drum pad elements, each with a class name of drum-pad, a unique id that describes the audio clip the drum pad will be set up to trigger, and an inner text that corresponds to one of the following keys on the keyboard: Q, W, E, A, S, D, Z, X, C. The drum pads MUST be in this order.
* Within each .drum-pad, there should be an HTML5 audio element which has a src attribute pointing to an audio clip, a class name of clip, and an id corresponding to the inner text of its parent .drum-pad (e.g. id="Q", id="W", id="E" etc.).
* Clicking on a .drum-pad element plays the audio clip contained in its child audio element.
* Pressing the trigger key associated with each .drum-pad plays the audio clip contained in its child audio element (e.g. pressing the Q key should trigger the drum pad which contains the string "Q", pressing the W key should trigger the drum pad which contains the string "W", etc.).
* When a .drum-pad is triggered, a string describing the associated audio clip is displayed as the inner text of the #display element (each string must be unique).

***

## Project Data
Audio files:  
https://s3.amazonaws.com/freecodecamp/drums/Heater-1.mp3  
https://s3.amazonaws.com/freecodecamp/drums/Heater-2.mp3  
https://s3.amazonaws.com/freecodecamp/drums/Heater-3.mp3  
https://s3.amazonaws.com/freecodecamp/drums/Heater-4_1.mp3  
https://s3.amazonaws.com/freecodecamp/drums/Heater-6.mp3  
https://s3.amazonaws.com/freecodecamp/drums/RP4_KICK_1.mp3  
https://s3.amazonaws.com/freecodecamp/drums/Kick_n_Hat.mp3  
https://s3.amazonaws.com/freecodecamp/drums/Dsc_Oh.mp3  
https://s3.amazonaws.com/freecodecamp/drums/Cev_H2.mp3

***

## Final Project
https://myrmidonut.github.io/fcc_frontend_drum_machine

***

## Preview Images
### Main Screen:
![Drum Machine](readme_images/drum-machine.png)
