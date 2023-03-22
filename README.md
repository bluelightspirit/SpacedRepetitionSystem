# SpacedRepetitionSystem

## A Java flash card tool that uses the terminal where the user can study & learn by creating their own questions & cards, then have the program tell what cards they should study depending on the difficulty of the question, similar to the tool [Anki](https://apps.ankiweb.net/)

## How does anyone download & run the tool?

Anyone should be aiming to see the tool that looks like this:

![image](https://user-images.githubusercontent.com/22280271/227016551-19419d57-7ea2-4df9-a876-34d52ac46115.png)

First, all of the 3 classes, [Main.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.java), [Deck.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Deck.java), & [Card.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Card.java) must be downloaded. To do that, it is suggested to download the ZIP file from [Releases](https://github.com/bluelightspirit/SpacedRepetitionSystem/releases) or copy the repo from a console like Git. It is also suggested to double check if the text-based files are in the same folder if the user plans to use the example text-based files. 

Then, [Main.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.java) should be compiled. After that, [Main.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.java)'s main method should be ran using any IDE that supports Java such as [IntelliJ](https://www.jetbrains.com/idea/download/) or [BlueJ](https://www.bluej.org/). 

Note: [IntelliJ](https://www.jetbrains.com/idea/download/) requires [Main.class](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.class) to run, or could be reformatted by having the src folder & stuff if the user knows how to run from [Main.java](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.java) there.

Other Note: [BlueJ](https://www.bluej.org/) will be easier to run by also downloading [package.bluej](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/package.bluej).

Then, to use the tool, the user first should start up the tool that uses the terminal.

In [IntelliJ](https://www.jetbrains.com/idea/download/), the way to open the project is to press "Open", navigate to where the 3 classes of code are, then select that folder as shown below & press "OK" at the bottom.

![image](https://user-images.githubusercontent.com/22280271/227029080-b385c84f-2943-41b9-ad91-b03c60c5c8cb.png)

Since this project was designed to also have compatibility with [BlueJ](https://www.bluej.org/), after the project is opened, open [Main.class](https://github.com/bluelightspirit/SpacedRepetitionSystem/blob/main/Main.class) within [IntelliJ](https://www.jetbrains.com/idea/download/).

![image](https://user-images.githubusercontent.com/22280271/227033853-949c1972-09e7-4317-8815-c596f48b60c9.png)

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

## How does anyone use the tool?

Within [BlueJ](https://www.bluej.org/) or [IntelliJ](https://www.jetbrains.com/idea/download/), the user can type "1", "2", "3", or "4" to study a deck of cards, add cards to a deck of cards, create a new deck of cards, or exit the tool!

![image](https://user-images.githubusercontent.com/22280271/227028115-b3dc8f4d-fd65-4eec-9b25-d2adf4692f71.png)

Typing "3" then [ENTER] in should ask the user to create a new deck of cards, like this:

![image](https://user-images.githubusercontent.com/22280271/227036298-969c6a5f-7cde-418b-98e4-12a0f50f4b5f.png)

Then, the user could type in the deck name they desire to use (duplicates & certain characters depending on the operating system used are not allowed)

![image](https://user-images.githubusercontent.com/22280271/227036394-4139961d-b480-4012-9a9c-bc55a4c30ca4.png)

Typing "2" then [ENTER] in should ask the user to add cards to a deck of cards, like this:

![image](https://user-images.githubusercontent.com/22280271/227036560-8dc02e20-c735-4207-a9b3-7fad3d391f5a.png)

Then, the user can choose a deck to add cards to & set their question & answer, like this:

![image](https://user-images.githubusercontent.com/22280271/227036706-2c8e4909-4e56-4bf5-9d02-b5e74978bbdb.png)

The user then could either keep making questions & answers, or type in "stop" to go back to the options, like this:

![image](https://user-images.githubusercontent.com/22280271/227036940-b58856d2-9292-4816-ba67-2a50dac33c45.png)

Then, after they added cards to that deck, they could now study it!

Typing "1" then [ENTER] in should ask the user to choose from one of the decks available, like this:

![image](https://user-images.githubusercontent.com/22280271/227037179-9f40d4e5-bd65-4358-92ff-c3c5f7820a1f.png)

Then, the user could choose a deck to study from then [ENTER], like this:

![image](https://user-images.githubusercontent.com/22280271/227037295-63034cdf-098d-4ac3-897c-229d29b5143a.png)

Then, the question will appear like so:

![image](https://user-images.githubusercontent.com/22280271/227037348-28ceaa41-84d9-45b5-b628-d9f938e0a22b.png)

It is optional to type in the answer in the box. Either way, pressing [ENTER] will lead to the answer being shown when ready, which should look like this:

![image](https://user-images.githubusercontent.com/22280271/227037599-ce1d5c19-6764-45e3-81c3-00335d46da22.png)

Then, the user can type in "w"/"wrong", "d"/"difficult", "c"/"correct", or "e"/"easy".

Telling the program the user got the wrong answer by typing in "w" then [ENTER] should result in the question eventually coming back again. Since this deck has only 1 card, it instantly comes back to the card just answered to ask it again:

![image](https://user-images.githubusercontent.com/22280271/227038153-71d1fb95-c6dc-4a1e-9e41-cac89acb5d95.png)

[ENTER] should of course show the options for the user to choose from again in the difficulty of the question.

![image](https://user-images.githubusercontent.com/22280271/227038500-c452f22e-7130-43e2-b93e-997a97034cc8.png)

If the user inputted "d" then [ENTER] in, the date the question would be due would generally be earlier than inputting "c" or "e" then [ENTER] in since more difficult questions are meant to be repeated more often than easier ones due to the design of [Spaced Repetition](https://en.wikipedia.org/wiki/Spaced_repetition).

## How to save?

The program auto-saves the .deck files in the decks folder any time they create a new deck, stop giving questions & answers while adding cards to a deck, & whenever the user inputs the difficulty in the question they're studying in & entering that input. Pressing some "save" button over and over is not required. Re-running the program should keep all of the save data. 

If the user want to make sure it saved or not, the user could check the decks folder the code is in, assuming the user at least used the tool once before typing in 1-3 & entering before.

![image](https://user-images.githubusercontent.com/22280271/227039775-8cf4396c-a34c-43eb-b682-a728c955832b.png)

## How does the tool work?

The tool works as a flash-card program that allows users to study things they wish to memorize. It will represent a flash card containing a question, such as "Are bandits good?" and an answer, such as "No!"

The program does not ask the user to type the answer in, or check if they got it right. However, if the user desires, they could type in the answer before pressing [ENTER], which would indicate they are ready for the answer when they press [ENTER]. After that, it will show the user the answer & ask the user if they got it right or not.

The difficulty of the answers to the questions can be judged by the user, from (W)rong, (E)asy, (C)orrect, & (D)ifficult. Difficult questions will be shown earlier than correct ones, correct ones will be shown earlier than easy ones, & wrong ones will be shown in the same study session/same day. There will also be a streak algorithm if the user gets a certain question correct enough days in a row without getting anything wrong, which scales up to a shorter date if easier & a longer date if more difficult. This idea is called [Spaced Repetition](https://en.wikipedia.org/wiki/Spaced_repetition) which has been shown to be an effective way to memorize info.

The program also allows the user to create new decks & add new cards to a deck. The user could also manually type in the cards they want to add by editing the .deck file they wish to, or even create their own .deck file as long as it is in the "/decks" folder in the same position of where the 3 classes for the code are at.

## What did I learn?

1. How to search a directory for only ".deck" or any extension files.
2. How to create a directory/folder.
3. How to create a file using Files specifically.
4. How to use Java's LocalDate API.
5. How to use Java's DirectoryStream API, as well as how to convert their stream ArrayList of Path's to Strings.
6. How to use Java's System.getProperty() within Java's System class to get the operating system the program is running on & to get the file location (reverted the get file location part this way since it wasn't necessary to use that to get the file location of the .class it is running from specifically).
7. How to use PrintWriter that is declared & set from a different class to save specific Cards from the Card.java class, depending on what Deck fileName should be used.
8. What file names were not allowed in certain operating systems from research.

## What goal(s) did I accomplish?

I created a tool where user could study flash cards based on a difficulty algorithm telling them when they should study certain questions versus others, learned how to use several API's, learned how to create directories & folders wherever I wanted to in Java, & learned how to check the operating system the code is running on!

## Compiling

This program uses solely Java to compile.
