# Sequence Master

A memory-based sequence game where players must remember and repeat increasingly longer color patterns.

## How to Play

1. Watch as a new color lights up each round
2. Repeat the entire sequence from the beginning
3. Each round adds one more color to remember
4. One mistake ends the game!

**Example:** Round 3 shows Blue. You must press Green (round 1), Red (round 2), and Blue (this round).

## Controls

### Desktop
- **Q** - Green (top-left)
- **W** - Red (top-right)
- **A** - Yellow (bottom-left)
- **S** - Blue (bottom-right)
- **Space** - Start game

### Mobile
- Tap the color buttons directly
- Touch-optimized interface

## Features

- Clean, responsive design that works on all devices
- Audio feedback for each color
- Score tracking with Mesa SDK integration
- Leaderboard support (accessible via Mesa portal)

## Technologies

- Vanilla JavaScript (no frameworks)
- Web Audio API for sound generation
- Mesa SDK for leaderboard and user management
- Single HTML file for easy deployment

## Running the Game

Simply open `simon.html` in a modern web browser. No build process or dependencies required.

## Mesa SDK Integration

This game integrates with the Mesa SDK to:
- Submit scores to a global leaderboard
- Track user progress
- Enable social features via the Mesa portal

Scores are automatically submitted when logged in through the Mesa platform.

## License

MIT
