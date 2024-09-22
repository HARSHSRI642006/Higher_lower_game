# Higher_lower_game

**Overview**
The Higher_lower_game is a simple Python game where the player is presented with two entities (such as social media platforms or celebrities), and the goal is to guess which one has more followers. The game continues with the player comparing different entities until they make a wrong guess. The player's score increases with each correct guess.

**Features**
ASCII art for logos and comparison interface to enhance the visual appeal.
We randomized entity comparison to make each round unpredictable.
Recursive gameplay allows the player to keep playing as long as they make correct guesses.
Score tracking across rounds to show the player their progress.
**Requirements**
Python 3.x
No additional libraries are required for this game.
**How to Play**
Run the Python script.
You will be presented with two entities (e.g., social media platforms) and their descriptions.
Based on your knowledge, type A if you think the first entity has more followers or B if you think the second entity has more.
If your guess is correct, your score will increase, and the game will continue with a new comparison.
If your guess is incorrect, the game will end, and your final score will be displayed.
Example

Compare A: Instagram, A social media platform, from USA
  .----------------.  .----------------. 
 | .--------------. || .--------------. |
 | | ____   ____  | || |    _______   | |
 | ||_  _| |_  _| | || |   /  ___  |  | |
 | |  \ \   / /   | || |  |  (__ \_|  | |
 | |   \ \ / /    | || |   '.___`-.   | |
 | |    \ ' /     | || |  |`\____) |  | |
 | |     \_/      | || |  |_______.'  | |
 | |              | || |              | |
 | '--------------' || '--------------' |
 '----------------'  '----------------' 

Against B: Twitter, A microblogging platform, from USA
Who has more followers? Type A or B: a
You are right! Your current score is 1.
**Game Flow**

Logo Display: The game starts by displaying the ASCII art logo of the game.
Comparison Round: Two random entities are picked from the dataset, and the player is asked to guess who has more followers.
Score Calculation: If the player guesses correctly, their score is increased by 1, and the game continues. If they guess wrong, the game ends, and their final score is displayed.
Game Restart: To restart the game, simply rerun the script.

**How to Modify the Data**

The dataset is a list of dictionaries containing the following fields for each entity:

name: The name of the entity (e.g., Instagram, Twitter).
description: A brief description of the entity.
country: The country where the entity is based.
follower_count: The number of followers the entity has.
You can add or modify the entities in the data list as needed:


data = [
    {"name": "Instagram", "description": "A social media platform", "country": "USA", "follower_count": 1000},
    {"name": "Twitter", "description": "A microblogging platform", "country": "USA", "follower_count": 500},
    # Add more data here
]


Enjoy the game and challenge your knowledge about popular social media platforms and other entities!




