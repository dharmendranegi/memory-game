# memory-game

This is a simple but complete memory matching game themed around AWS services,  designed to be educational and fun while familiarising players with AWS service  icons. 

## Game Features

The game uses 8 AWS services (EC2, S3, Lambda, DynamoDB, CloudFormation, RDS, SNS, SQS) with their icons
Each service appears twice, creating 16 cards total

1. Cards are arranged in a 4x4 grid
2. 4x4 grid with 16 cards (8 pairs)
3. Tracks the number of moves you make
4. Counts matches (out of 8 possible pairs)
5. Includes a timer to measure how long it takes to complete
6. Has a reset button to start a new game

## How It Works

1. Cards are randomly shuffled at the start
2. You click on cards to flip them over
3. If two flipped cards match, they stay face up
4. If they don't match, they flip back over
5. The game ends when all 8 pairs are matched
6. Upon completion, it shows your performance (moves and time)

## Technical Details

1. It's a standalone HTML file with embedded CSS and JavaScript
2. Uses modern web technologies like CSS Grid for layout
3. Implements the Fisher-Yates algorithm for card shuffling
4. Uses CSS transitions for the card flip animation

You can open this file in any web browser to play the game.
