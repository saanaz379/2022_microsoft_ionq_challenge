# Project: QKDelephone

## Team Name: The Qeys to Success
Aengus McGuinness, Krishnaveni Parvataneni, Saarah Nazar, Swetha Kandeepan

## Purpose
The purpose of this project is to create a telephone-esque game using Quantum Key Distribution, allowing for this concept to become more intellectually accessible to the public. Our code generates a series of random bits and bases on which to create qubits that encode a message. Our reciever then measures the message with their own random bases. They then share their bases and throw out the bits without matching bases. The final result is their own secure key! Additionally, our program can model the impact that any number of interceptors will have on the key.

## Creativity
Our original vision for this project was to emulate a modular version of Quantum Key Distribution where players can fill the positions of sender, reciever, and "eavesdropper". The current module allows for the sender to attempt to securely and correctly transmit a message to the reciever, while the "eavesdropper" tries to intermittently intercept the message.

## Impact
Our code idea has 3 kinds of impacts — education, entertainment, and information security. One of the main goals of our project was to make knowledge of QKD more widespread, allowing for more people to access it and be able to use a QKD algorithm. As for the entertainment impact, our game has similarities to the fun childhood game "telephone". In the game of telephone, there are multiple players who try to pass a message down the line. As the message is transmitted, it becomes increasingly garbled, just like how a key communicated through QKD might change with the presence of an interceptor. This game is also a model for more secure information exchange, giving it the ability to make the pubic more knowledgable about quantum cryptography, which is employed by governments, militaries, and banks.

## Tutorial
Over the course of this hackathon, we weren't able to create graphics for our game, so currently it is a command line game. Run our file with any python interpreter such as python3 and it will print to the command line.

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

![2022-01-30-1](https://user-images.githubusercontent.com/80733759/151708026-35633f2a-2194-4a45-89ba-316eb509d699.png)

## Our experience at iQuHACK
We thought that iQuHACK was really fun, and the people here were nice and helpful. It was a great opportunity to meet other people who were interested in similar fields, develop our coding skills, and further our understanding of quantum computing. Overall, it was a really enriching experience!

## Date
January 29-30, 2021
