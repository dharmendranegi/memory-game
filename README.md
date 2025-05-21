# memory-game
This is a simple but complete memory matching game themed around AWS services,  designed to be educational and fun while familiarising players with AWS service  icons. 

## Game Features
The game uses 8 AWS services (EC2, S3, Lambda, DynamoDB, CloudFormation, RDS, SNS, SQS) with their icons
Each service appears twice, creating 16 cards total
• Cards are arranged in a 4x4 grid
• 4x4 grid with 16 cards (8 pairs)
• Tracks the number of moves you make
• Counts matches (out of 8 possible pairs)
• Includes a timer to measure how long it takes to complete
• Has a reset button to start a new game

## How It Works
1. Cards are randomly shuffled at the start
2. You click on cards to flip them over
3. If two flipped cards match, they stay face up
4. If they don't match, they flip back over
5. The game ends when all 8 pairs are matched
6. Upon completion, it shows your performance (moves and time)

## Technical Details
• It's a standalone HTML file with embedded CSS and JavaScript
• Uses modern web technologies like CSS Grid for layout
• The card images are loaded from AWS's servers
• Implements the Fisher-Yates algorithm for card shuffling
• Uses CSS transitions for the card flip animation

You can open this file in any web browser to play the game.
