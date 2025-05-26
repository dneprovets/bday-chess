# Chess Master 🦁

A beautiful, modern chess game with a strong AI opponent, built with vanilla JavaScript and featuring an elegant iOS-style design.

## Features

🎯 **Dual AI System**
- **Full Mode**: Stockfish WebAssembly (requires HTTP server)
- **Fallback Mode**: Enhanced intermediate engine (direct file opening)
- Checkmate detection and strategic play
- Good capture evaluation and piece development

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

### Quick Start (Enhanced Fallback Engine)
1. Open `index.html` directly in your web browser
2. Wait for the FintechFarm logo loading screen
3. Click on a piece to select it
4. Click on a highlighted square to move
5. For pawn promotion, choose your desired piece from the dialog
6. Enjoy playing against the enhanced AI!

### Full Stockfish Engine (Recommended)
For the strongest AI experience, run with a local server:
```bash
# Navigate to the game directory
cd /path/to/bday-chess

# Start a local server (choose one):
python3 -m http.server 8000
# OR
node -e "require('http').createServer(require('fs').readFile.bind(require('fs'))).listen(8000)"
# OR
npx serve .

# Open in browser
open http://localhost:8000
```

## Technical Details

- **Game Logic**: chess.js library (move validation, rules, game state)
- **AI Engine**: Stockfish WebAssembly (move calculation only)
- **Memory**: Optimized with 16MB hash limit and single thread
- **AI Level**: Intermediate (Skill Level 10, Depth 8)
- **Fallback**: Enhanced engine when Stockfish unavailable
- **UI**: Modern iOS-style interface with smooth animations

## Files Structure

```
├── index.html          # Main game file
├── chess-browser.js    # Chess.js library
├── stockfish.js        # Stockfish WebAssembly engine
├── content/
│   ├── ff-logo.png    # FintechFarm logo
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
- AI Engine: [Stockfish](https://stockfishchess.org/) WebAssembly
- Design: Custom iOS-inspired interface
- Sounds: Custom audio effects

---

**Enjoy your chess game! 🦁♟️**
