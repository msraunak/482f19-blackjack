## Assignment 01: A Simplified Blackjack Game
## Assigned: Tue, Sep 17, 2019
## Due: Mon, Sep 30, 2019 11:59pm

## CS 482: Software Engineering
## Loyola University Maryland
## Fall 2019

__The Program__: This program is aimed at involving everyone in the class, especially if you have never
done so before, to get started on app development using android studio. Another objective is to
streamline some of your coding practices including your program design and coding habits. You will
be doing this assignment in pairs. Special attention will be given to identifier naming, commenting etc.
You are going to write javadoc style comments. Follow the coding-convention and commenting
guidelines that I have made available in Moodle.
You will develop ‘’SimpleBlackJack” as an Android App in Java that allows the users to play a game
of simplified BlackJack. The player of the SimpleBlackJack will try to get as close to 21 as possible,
without going over (called bust). The BlackJack player’s objective is to beat the dealer by either
outscoring the dealer or having the dealer go bust. Blackjack may be played with one or two decks of
52-card decks. Here are some more details of the requirements.
1. SimpleBlackJack will be played by the dealer (the computer) and one player.
2. Ace will be counted as a 1 or 11, whichever fits better. King, Queen, and Jack will all be
counted as 10. The other cards will be counted at pip value.
3. The value of a hand is the sum of the point values of the individual cards.
4. A &quot;blackjack&quot; is the highest hand, consisting of an ace and any 10-point card (Queen, King,
or Jack), and it outranks all other 21-point hand.
5. The dealer will give two cards to the player and two cards to herself. Both the player’s and
the dealer’s card-pair will be shown face-up.
a. If the player has a blackjack, then the player wins the game.
b. If the dealer has a blackjack, then the player loses the game.
c. If both the player and the dealer have blackjacks, then it is a tie.
6. The player will have the first turn. He can go for Hit or Stop.
7. Hit: Player touches a button title Hit, which draws another card. If this card causes the
player&#39;s total points to exceed 21 (known as &quot;breaking&quot; or &quot;busting&quot;) then he loses. A
player can at most push Hit 3 times after the first two cards that were drawn at the
beginning of a game round. Thus, there will be at most 5 cards drawn by the player.
8. After 3 Hits, the Hit button should be disabled for the Player.
9. Stop: The player may choose to stop at any point after the initial two cards and before the
three Hits i.e. before the drawing of the three new cards. When the 3 cards are drawn, it
will become the dealer’s (i.e., the Computer’s) round.
10. Dealer can also draw up-to three new cards. Dealer’s drawing will be automatic (no
pressing of Hit button is needed). The dealer’s objective is, of course, to win and to make
you lose. Once the dealer has either gone bust, stopped or have drawn all three cards, the
app will show result of the game, which will be one of the following three scenarios:
10.1 The Player has won
10.2 The Dealer has won
10.3 The round is a Tie

11. SimpleBlackJack will have a “New Game” button that starts a new game. The player can hit
the “New Game” button at any time. If this button is hit in the middle of the game, it will
cancel the current game and start a new one.

What you will need to do:
1. Think about the program before starting to code. What will be the underlying model of your
App. This includes identifying the classes you will need and how they will relate to each other.
2. __Coding Documentation and Design__
2.1 Document your program with Javadoc style comments for field names, methods and
classes.
2.2 Use descriptive and meaningful identifier names (variables, methods and classes).
2.3 Have a reasonable design. Do not use a monolithic class to do everything. Ideally you
should be using a model-view-controller (MVC) design pattern.

3. __Collaboration and Submission__

 a. Commit your code to a github. Both members will collaborate through git hub. Invite
me (github username: msraunak) as a collaborator to your github project.
 b. Both team members should have multiple commits to your Github repository. in the
git repository.
 c. Make a video of less than 3 minutes long of your program demo, upload it to
youtube and submit the link. You can use a free screen capture program like
Camstudio (http://camstudio.org) or screencast-o-matic (https://screencast-o-
matic.com), or simply hold your phone towards your laptop to record the demo of
your program.

4. __Effort Estimation and Work division__
a. Before you begin the assignment, individually, make an estimation of how many
effective (non-comment) lines of code you will need to write and how many hours do
you think you will spend working on this assignment.
b. Write a brief report (a few paragraphs) describing the learning and development
process, the worked division (who wrote how many lines of code), and how many
hours each of you ended up spending on doing research/learning and actual writing
of the program.

Notes:
● Grading Breakdown: This assignment is to be done in pairs. Both members of the pair
should contribute to the development. If one member of the pair has not done any android
development before s/he should do the bulk of the work. Here is the breakdown of the
grading:
a. Working program that supports the feature list: 50
b. Following strong coding convention, use of meaningful
and descriptive identifier, class, method names etc.: 15
c. Javadoc style comments: 15
d. Report on estimation and work division: 20
● Do not wait till the last few days to do this assignment. Start working on it right away.
● Late Submission: Following the general principle specified in the Syllabus, for this assignment,
a late penalty of 10% will be applied if submitted within 24 hours of the due date (Sep 30). If
you submit after 24 hours of the due date but within 72 hours, you will receive a penalty of
20%.
