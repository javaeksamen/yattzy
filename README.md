# yattzy
How to run this program
Build and test executable jar file
First, clone the project
run mvn clean package
add task-manager.properties file
add dataSource.url
add dataSource.username
add dataSource.password
To start the program, run the command java -jar target/yatzy-game-1.0-SNAPSHOT.jarin the terminal

 GAME Explanation.
 
The objective of the game is to score points by rolling five dice to make certain combinations. The dice can be rolled up to three times in a turn to try to make various scoring combinations and dice must remain in the box. A game consists of thirteen rounds. After each round the player chooses which scoring category is to be used for that round. Once a category has been used in the game, it cannot be used again. The scoring categories have varying point values, some of which are fixed values and others for which the score depends on the value of the dice. A Yahtzee is five-of-a-kind and scores 50 points, the highest of any category. The winner is the player who scores the most points.

The game consists of a number of rounds. In each round, a player gets three rolls of the dice, although they can choose to end their turn after one or two rolls. After the first roll the player can save any dice they want and re-roll the other dice. This procedure is repeated after the second roll. The player has complete choice as to which dice to roll. It is possible to re-roll both dice that were or were not rolled before.

Object of game

The object of Yahtzee is to obtain the highest score from throwing 5 dice.
The game consists of 13 rounds. In each round, you roll the dice and then score the roll in one of 13 categories. You must score once in each category. The score is determined by a different rule for each category.
The game ends once all 13 categories have been scored.

Game Start

To start with, roll all the dice. After rolling you can either score the current roll (see below), or re-roll any or all of the dice.

You may only roll the dice a total of 3 times. After rolling 3 times you must choose a category to score.

You may score the dice at any point in the round, i.e. it doesn't have to be after the 3rd rol

Score.

You can score any roll in any category at any time, even if the resulting score is zero. Eg, you
can take 2-3-3-4-6 in the 5's category. It will score 0. This could be used near the end of a game to lose a poor roll against a difficult-to-get category that you've failed to fill 
