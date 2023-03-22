# SpacedRepetitionSystem

## A Java flash card tool that uses the terminal where the user can study & learn by creating their own questions & cards, then have the program tell what cards they should study depending on the difficulty of the question, similar to the tool [Anki](https://apps.ankiweb.net/)

## How does anyone use the tool?

Anyone should be aiming to see the tool that looks like this:

![image](https://user-images.githubusercontent.com/22280271/227016551-19419d57-7ea2-4df9-a876-34d52ac46115.png)

First, all of the 3 classes, [Main.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.java), [Deck.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Deck.java), & [Card.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Card.java) must be downloaded. To do that, it is suggested to download the ZIP file from [Releases](https://github.com/bluelightspirit/SpacedRepetitionSystem/releases) or copy the repo from a console like Git. It is also suggested to double check if the text-based files are in the same folder if the user plans to use the example text-based files. Then, [Main.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.java) should be compiled. After that, [Main.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.java)'s main method should be ran using any IDE that supports Java such as [IntelliJ](https://www.jetbrains.com/idea/download/) or [BlueJ](https://www.bluej.org/), although note [BlueJ](https://www.bluej.org/) has a slight compatibility issue with this project (fix is below after [IntelliJ](https://www.jetbrains.com/idea/download/)'s instructions)

Then, to use the tool, the user first should start up the tool that uses the terminal.

In [IntelliJ](https://www.jetbrains.com/idea/download/), the way to open the project is to press "Open", navigate to where the 3 classes of code are, then select that folder as shown below & press "OK" at the bottom.

![image](https://user-images.githubusercontent.com/22280271/227029080-b385c84f-2943-41b9-ad91-b03c60c5c8cb.png)

Since this project was designed to also have compatibility with [BlueJ](https://www.bluej.org/), after the project is opened, open [Main.class](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.class) within [IntelliJ](https://www.jetbrains.com/idea/download/).

In [IntelliJ](https://www.jetbrains.com/idea/download/), the way to run is to press this button at the top right or Shift+F10 on Windows:

![image](https://user-images.githubusercontent.com/22280271/227017226-8b51f1bc-0123-493f-a1c0-1cb9baf73212.png)

In [BlueJ](https://www.bluej.org/), the way to open the project first is to press Project -> Open Project -> Select the folder the 3 classes downloaded are in -> Select Folder or to simply double click "package" within that folder.

![image](https://user-images.githubusercontent.com/22280271/227033248-154d3a13-cfba-4d81-900b-a110a50dca82.png) 
![image](https://user-images.githubusercontent.com/22280271/227032260-e11af9b5-0851-4276-ab5c-67d10680a677.png)

After doing that, it should look like this:

![image](https://user-images.githubusercontent.com/22280271/227017982-ee58d3d9-60d6-4665-ba6d-073c4db655d4.png)

Then, to run the code in [BlueJ](https://www.bluej.org/), right click "Main" then press "Compile" as shown below:

![image](https://user-images.githubusercontent.com/22280271/227018122-a3e15870-af89-46f0-a3a4-b674e1a7337c.png)

Navigate back to this [BlueJ](https://www.bluej.org/) window, right click the Main box, then press void main(String[] args).

![image](https://user-images.githubusercontent.com/22280271/227019186-ab9a6643-9816-48d2-979e-2aa9db26b26c.png)

Finally, press "OK".

![image](https://user-images.githubusercontent.com/22280271/227027840-2c48b2b6-a3c1-4d3d-8645-d002bb428483.png)

Then, within [BlueJ](https://www.bluej.org/) or [IntelliJ](https://www.jetbrains.com/idea/download/), the user can type "1", "2", "3", or "4" to study a deck of cards, add cards to a deck of cards, create a new deck of cards, or exit the tool!

![image](https://user-images.githubusercontent.com/22280271/227028115-b3dc8f4d-fd65-4eec-9b25-d2adf4692f71.png)

## How does the tool work?

The tool works as a flash-card program that allows users to study things they wish to memorize. It will represent a flash card containing a question, such as "Are bandits good?" and an answer, such as "No!"

The program does not ask the user to type the answer in, or check if they got it right. However, if the user desires, they could type in the answer before pressing [ENTER], which would indicate they are ready for the answer when they press [ENTER]. After that, it will show the user the answer & ask the user if they got it right or not.

The difficulty of the answers to the questions can be judged by the user, from (W)rong, (E)asy, (C)orrect, & (D)ifficult. Difficult questions will be shown earlier than correct ones, correct ones will be shown earlier than easy ones, & wrong ones will be shown in the same study session/same day. There will also be a streak algorithm if the user gets a certain question correct enough days in a row without getting anything wrong, which scales up to a shorter date if easier & a longer date if more difficult. This idea is called [Spaced Repetition](https://en.wikipedia.org/wiki/Spaced_repetition) which has been shown to be an effective way to memorize info.

The program also allows the user to create new decks & add new cards to a deck. The user could also manually type in the cards they want to add by editing the .deck file they wish to, or even create their own .deck file as long as it is in the "/decks" folder in the same position of where the 3 classes for the code are at.

## Compiling

This program uses solely Java to compile.
