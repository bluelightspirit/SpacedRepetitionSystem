# SpacedRepetitionSystem

## A Java flash card tool that uses the terminal where the user can study & learn by creating their own questions & cards, then have the program tell what cards they should study depending on the difficulty of the question, similar to the game [Anki](https://apps.ankiweb.net/)

## How does the game work?

The game works as a flash-card program that allows users to study things they wish to memorize. It will represent a flash card containing a question, such as "Are bandits good?" and an answer, such as "No!"

The program does not ask the user to type the answer in, or check if they got it right. However, if the user desires, they could type in the answer before pressing [ENTER], which would indicate they are ready for the answer when they press [ENTER]. After that, it will show the user the answer & ask the user if they got it right or not.

The difficulty of the answers to the questions can be judged by the user, from (W)rong, (E)asy, (C)orrect, & (D)ifficult. Difficult questions will be shown earlier than correct ones, correct ones will be shown earlier than easy ones, & wrong ones will be shown in the same study session/same day. There will also be a streak algorithm if the user gets a certain question correct enough days in a row without getting anything wrong, which scales up to a shorter date if easier & a longer date if more difficult. This idea is called [Spaced Repetition](https://en.wikipedia.org/wiki/Spaced_repetition) which has been shown to be an effective way to memorize info.

The program also allows the user to create new decks & add new cards to a deck. The user could also manually type in the cards they want to add by editing the .deck file they wish to, or even create their own .deck file as long as it is in the "/decks" folder in the same position of where the 3 classes for the code are at.

## Compiling

This program uses solely Java to compile.
