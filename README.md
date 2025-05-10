ID5677583

Game Overview
Crazy Eights is a classic card game where the objective is to be the first player to get rid of all your cards. This implementation features:

Single-player gameplay against an AI opponent
Graphical interface with card animations
Multiple rounds of play
Complete scoring system
Game Rules
Basic Rules
Players take turns playing cards onto the discard pile
Cards must match the top card by either suit or rank
Eights are wild cards - they can be played anytime
When playing an eight, you choose the next suit
If you can't play a card, draw from the deck
If the deck is empty and you can't play, your turn is skipped
Scoring
When a player goes out, they score points for cards in opponent's hand
Eights = 50 points
Face cards (Jack, Queen, King) = 10 points
Other cards = face value (Ace = 1, Two = 2, etc.)
Multiple rounds are played, with the highest score at the end winning
Installation
Requirements
Python 3.7+
Pygame
Setup
Install dependencies:

pip install -r requirements.txt
Running the Game
Launch the game with:

python -m src.main
How to Play
Playing Cards: Drag cards from your hand to the center pile to play them
Drawing Cards: Click the "Draw Card" button when you can't play
Wild Eights: After playing an eight, click on a suit button to choose the new suit
Game Rules: Click the "Rules" button in the top-right corner to view the rules
Features
Animated AI Moves: Watch as the computer plays cards with smooth animations
Suit Selection: Clear interface for choosing suits after playing an eight
Round & Game Summary: Detailed scoring information between rounds
Card Animations: Smooth card movements and rotations
Project Structure
The game is organized into the following modules:

src/
├── main.py           # Entry point
├── game.py           # Main game logic
├── constants.py      # Game constants
├── card.py           # Card implementation
├── deck.py           # Deck implementation
├── player.py         # Human player class
├── ai_player.py      # AI player implementation
├── ui/               # UI components
│   ├── button.py     # Button implementation
│   ├── card_sprite.py # Card sprite implementation
│   └── text.py       # Text rendering
├── utils/            # Utility modules
│   ├── asset_manager.py # Asset management
│   └── state_machine.py # Game state management
└── assets/           # Game assets
    ├── cards/        # Card images
    └── sounds/       # Game sounds
Development
Future Enhancements
Multiplayer support
Additional card game variants
Customizable card backs and table themes
Difficulty levels for AI
Credits
Card assets from Kenney (www.kenney.nl)
Sound effects from OpenGameArt.org
Fonts from Google Fonts
