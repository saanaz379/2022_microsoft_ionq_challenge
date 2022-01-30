# Project: QKDelephone

## Team Name - The Qeys to Success
Aengus McGuinness, Krishnaveni Parvataneni, Saarah Nazar, Swetha Kandeepan

## Purpose
The purpose of this project is to create a telephone-esque game using Quantum Key Distribution, allowing for this concept to become more intellectually accessible to the public. Our code generates a series of random bits and bases on which to create qubits which encode the message. Our reciever then measures the message with his own random bases. They then share their bases and throw out the bits without matching bases. They now have their own secure keys! Our program can also model the impact on the keys with any number of interceptors as well. 

## Creativity
Our original vision for this project was to emulate a modular version of Quantum Key Distribution where players can fill the positions of sender, reciever, and "eavesdropper," of which we created a module. The current module allows for the sender to attempt to securely and correctly transmit a message to the reciever, while the "eavesdropper" would try to intermittently intercept the message.

## Impact
Our code idea has 3 kinds of impacts - education, entertainment, and information security. One of the main goals of our project was to make knowledge of QKD more widespread and allow for more people to access and be able to use a QKD algorithm, which gives our code an educational impact. As for the entertainment impact, our game is very similar to a game of telephone, which is a really fun childhood game. In the game of telephone, there are multiple players who try to pass a message down the line. Over time, the message becomes more and more deformed, which adds to the game's funniness. This game is also a model for more secure information exchange, and such models, as an effect of the educational impact can have a great impact on Cryptography.

## Tutorial
During the course of this hackathon, we weren't able to create graphics for our game so currently it is a command line game. Just run our file with any python interpreter such as python3 and it will print to the command line.

## Future Improvements
Make the game interactive
> Using argparse to allow the user to choose number of interceptors and message

Graphical User Interface
> Create a graphical interface through PyGame or cmu-graphics

More interactive players
> Change the interceptors to actual people who can interactively eavesdrop 

Optimize the number of bits
> Find the most efficient number of bits and qubits for the QKD

Upload to a game platform
> Upload a version of the game to an app store or another game hoster


## Visualizations 
<img width="263" alt="Screen Shot 2022-01-30 at 7 51 41 AM" src="https://user-images.githubusercontent.com/80733759/151706839-9d7ecc17-40f2-4646-bd10-63450ed9bd6f.png">

**Fig 1: 4 types of circuits used**

## Our experience at iQuHack
We all thought that iQuHack was really fun, and the people here were really nice. It was a great opportunity to meet other people who were interested in similar fields, and we thought it was a really interesting experience.

## Presentation
https://docs.google.com/viewer?url=https://github.com/kparvataneni12/2022_microsoft_ionq_challenge/files/7966332/iQuHACK2022.pdf


## Date
January 29-30, 2021
