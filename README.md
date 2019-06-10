# Homework 3: Specification

## General Application Requirements
- There is no login required or account tracking for this application. (COMPLETE)
- The organizer can add as many people to the game room as needed without room capacity constraints. (COMPLETE)

## Organizer
Organizers can be team leaders, teachers, managers or any other leadership role. (Not a requirement, but more of a social expectation)

### Software must include these *functionalities*:

- When the organizer navigates to our website, they will be able to choose to start a new game or join an existing one. (COMPLETE)
- A unique room code will be assigned once organizers choose to start a new game. (COMPLETE)
- Room number must consist of a unique combination of numbers, letters of the alphabet, and 8 characters (inclusive). (COMPLETE)
- The organizer will have the ability to share the randomly generated room code to participants by selecting the copy icon which will copy to the clipboard and paste on preferred messaging platform.	(COMPLETE)
- The organizer is able to navigate to the room settings after creating the room by a single action. (COMPLETE - this is where the organizer can select how many questions they would like in a single game etc)
- Organizer is able to configure in the room settings if the game should include an compatibility analysis or to show rankings. A compatibility analysis will determine which players are compatible with each player. The rankings will display how well each player did in the game. (IMPOSSIBLE - The reason that it is possible is that there was no way we could organize the players answers in a way that allowed us to compare them, since players and questions were stored separately. We could not find a way to store it in a way that fit the architecture of our code and fulfilled this requirement. We also had difficulty resolving how we could compare every single player with each other, especially for a large room. Additionally, the ranking feature was not coherent because there is no "right answer" in the context of this game.)
- Organizer is able to change the default room name by typing the name of their choosing in the text field located in the room setting screen. This room name will only accept text or numbers but, no special characters. (COMPLETE)
- After the organizer has adjusted their preferred settings, they may navigate to the category page by a single action. (COMPLETE)
- Organizer is able to choose from a category of questions. The Organizer has the opportunity to select:
    - Sports (COMPLETE)
    - Travel (COMPLETE)
    - Sports (COMPLETE)
    - Music (COMPLETE)
    - Movies (COMPLETE)
    - Books (COMPLETE)
    - Food (COMPLETE)
    - Animals (COMPLETE)
    - Random: If the Organizer selects the random button then, their set number of randomly selected questions will be determined from the above categories.
    - Customize: The Organizer can create their own questions. After clicking on the customize option, the organizer will be directed to a screen with a card deck. Each card deck will have an input box for the organizer to type in their question. There is no limitation on what the organizer can type in as the question. The organizer will have the option of adding 5 questions (the default). To add more custom questions, the organizer will need to press the button that will direct them to the room settings and change the number of questions to appear in a single game. Once they have selected their desired number of questions, they will be able to press a button to return to the card deck and input more/less questions. Once they have added a question and corresponding multiple choice answers to the number of questions they have set in the room settings they will be prompted to a waiting room. (COMPLETE)
- After the organizer has chosen a category, they will have the option to click on a button that will create a room. This will lead them to a waiting room where the organizer will be able to oversee how many people has joined the room and determine whether to begin the game by selecting a button to start the game. (COMPLETE)
- There must be at least two people including organizer in the room to start the game. If the Organizer presses the button to start the game without having at least two people then, an error message will show and prompt the Organizer to begin when they have enough people. (COMPLETE)
- Once the game has started, every new question will be displayed initially to the Organizer and they will determine whether they wish to display the question for every player to answer by pressing on a button that will publish the question. Likewise, they have the option to skip the question without showing the question to players in the room by pressing the a button.
- Organizer is able to see how many people answered the question at all times through a number counter on their screen.
- Organizer’s will oversee the entire game, by seeing what the participants have answered and how many participants have answered.
- Organizer does not have the ability to input their own answers to the questions.
- If the organizer would like to cancel the game, they have the option to do so by clicking a button at any point before and during the game.
- When they click on the button to cancel the game, there will be an alert message confirming that they would like to cancel the game. This requires the organizer to click another button to return back to the game or cancel the game.
- If the game has been cancelled, the organizer will see an alert message indicating that the game has been cancelled. The organizer can click outside of the alert message or click a button to close the message and the organizer will be redirected to the following screen.
- If the game has been completed or cancelled, the screen will display the option to restart the game or to view analysis of the participant’s answers.
The organizer can restart the game within the same room by pressing a button. This in turn will prompt the Organizer to select a new category of questions to play with.
- If the organizer would not like to restart the game, they may choose to the analysis mode.
- Analysis will be based on the answers the players provided. We will display all the answers through a bar chart per question. We will show the number of participants that answered with option 1 or option 2. We will not show the names of the participants.

## Participants
### Software must include these *functionalities*:
- When the players navigates to our website, the players are able to join a specific game room by inputting the room code given by the Organizer. (COMPLETE)
- If players try to join a game while a game has begun, they will be denied and be shown a error message.
- The user will be prompted to type in their name into a textfield when trying to join a game room. This name must be at least two characters long without any special characters or numbers, maximum length is 10. (COMPLETE)
- Additionally, the Users are able to select an icon from a limited selection that the designers provided. The default icon will be the first icon from the selection. (COMPLETE)
- Once the players have inputted their name and chosen an icon, the players will be able to navigate to a waiting room, in which they are able view who has joined the game within the room.
- The game will not start unless the Organizer clicks on a button to start it. While waiting for the Organizer to begin the game, Players will see a loading display at the bottom of the screen under the list of players in the room.
- Once the game has begun, regardless, of the fact that the player is in vertical view or horizontal view the question and action buttons will repositions itself to fit both screen displays. (COMPLETE)
- Players are able to choose the answer to the question through a single action.
- If the player selects to cancel the game by clicking a button then, this specific player will be redirected to the landing page while the other players will still be playing the game.
- After answering each game question, the game will enter discussion time. On the player’s screen, it will display their answer in large font. This will allow the players to form groups with players who have chosen the same answer and discuss their answers. (IMPOSSIBLE - we could not find a timer that was compatible with our coding language and style. This requirement not central to the purpose of our app, as the organizer can facilitate this discussion in real life.)
- After the test has been completed, the players will see the loading page, whilst the organizer decides whether to restart the game or the analysis option.
- If the organizer has decided to end the game and show the analysis, the player will be shown the name of the player who has the most similar answers. (IMPOSSIBLE - as mentioned in the beginning)
- If the organizer has decided to restart the game then the screen will display the new question to every player in the room.
