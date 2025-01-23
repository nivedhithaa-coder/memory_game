FLIP CARDS

Overview:
This is a fun and interactive matching game where players match cartoon characters. The game features a grid of cards that players flip to find pairs. It is designed to enhance memory and concentration skills.
Deployed Link: https://nivedhithaa-coder.github.io/memory_game/TASK%203/

About the project:
The HTML layout consists of a header and a container for the game board. Tailwind CSS has been used for styling the elements of the web page. Game logic was implemented via JS. 
Game Logic: The cardList array contains the titles of all the cartoon characters that will be matched in this game. The cardSet array contains the cartoon characters in pairs. When the webpage loads, the shuffle function and start_game function are called.
shuffle(): This function randomly shuffles the elements of the cardSet array.
start_game(): This function arranges the shuffled elements in a 4 x 4 matrix format and calls the hide_cards function, which hides the cards under “bg.jpg.”
The select_cards() and check() functions allow us to flip any two cards that are clicked. If the selected cards match, they remain face-up. If they do not match, they flip back after a short delay of 1 second. The moves variable helps track the number of incorrect moves made.
The fresh() function is called whenever the restart button is clicked, helping to restart the game.

How to play the game?

This is a 4 x 4 matrix flip the card memory game.

The user is allowed to flip any two cards at a time. 
If the selected cards match, they remain unflipped.
Otherwise, the cards flip back after one second.
The number of moves taken by the user to match all the cards is tracked via the ‘Moves’ button on the header section.
The user can restart the game  at any time using the ‘Restart’ button in the header section.

