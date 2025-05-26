# Chess Master 🦁

A beautiful, modern chess game with a strong AI opponent, built with vanilla JavaScript and featuring an elegant iOS-style design.

## Features

🎯 **Strong AI Opponent**
- Advanced minimax algorithm with alpha-beta pruning
- Iterative deepening with 5-second time limit
- Sophisticated position evaluation
- Adaptive search depth based on game phase

🎨 **Beautiful iOS Design**
- Modern glassmorphism interface
- Smooth animations and transitions
- Lion emoji branding throughout
- Responsive design for all devices

♟️ **Complete Chess Rules**
- Full pawn promotion with piece selection
- En passant captures
- Castling (kingside and queenside)
- Check and checkmate detection
- Stalemate detection

🔊 **Smart Audio System**
- Capture sounds with fun notifications
- Victory applause for checkmate
- Silent moves for clean gameplay

📱 **Enhanced UX**
- Last move highlighting
- Possible move indicators
- Random motivational messages
- Auto-hiding notifications (3 seconds)

## How to Play

1. Open `index.html` in your web browser
2. Wait for the FintechFarm logo loading screen
3. Click on a piece to select it
4. Click on a highlighted square to move
5. For pawn promotion, choose your desired piece from the dialog
6. Enjoy playing against the strong AI!

## Technical Details

- **Engine**: Custom JavaScript chess engine using chess.js library
- **AI**: Minimax with alpha-beta pruning, transposition tables
- **Time Control**: 5-second maximum thinking time per move
- **Search Depth**: 1-8 plies with iterative deepening
- **Evaluation**: Material + positional + king safety + pawn structure

## Files Structure

```
├── index.html          # Main game file
├── chess-browser.js    # Chess.js library
├── content/
│   ├── ff-logo.png    # FintechFarm logo
│   ├── loop.mp3       # Move sound (unused)
│   ├── mat.wav        # Checkmate applause
│   └── roar.wav       # Capture sound
└── README.md          # This file
```

## Browser Compatibility

- Chrome/Chromium (recommended)
- Firefox
- Safari
- Edge

## Credits

- Chess logic: [chess.js](https://github.com/jhlywa/chess.js)
- Design: Custom iOS-inspired interface
- AI: Custom minimax implementation
- Sounds: Custom audio effects

---

**Enjoy your chess game! 🦁♟️**
