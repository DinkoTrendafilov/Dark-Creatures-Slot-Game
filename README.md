# 🦇 Dark Creatures — Slot Game

A mathematically verified 12-symbol slot game with collection bonuses, progressive jackpot, and a playable HTML5 demo.

## 🎮 Play the Game

**[▶️ Click here to play](https://dinkotrendafilov.github.io/Dark-Creatures-Slot-Game/)**

No download, no install — just open in your browser and spin.

## 📊 Game Overview

- **Reels / Rows:** 5 × 4
- **Lines:** 8 or 40
- **Symbols:** 12
- **RTP:** 96.0%
- **Volatility:** Medium-High
- **Hit Rate:** ~41.8% (1 in 2.4 spins)
- **Jackpot:** Progressive, 1 in 10,000 spins
- **Demo:** HTML5 / JavaScript

## 🎰 Core Mechanics

### Sequential Streak Multiplier

On consecutive winning spins, the multiplier grows:

2x → 3x → 4x → 6x → 8x → 12x → 16x → 20x → 24x → 30x → 36x → 40x → 45x → 50x → 64x

A 0-win spin resets back to 2x.

### 🦇 Night Creatures

Collect all four symbols at 5-of-5 on any line. Bonus: 500 × bet_per_line × random(2x–64x). Average hit: 1 in 18,867 spins.

### 🌑 Darkest Symbols

Collect both symbols at 5-of-5 on any line. Bonus: 10,000 × bet_per_line × random(2x–64x). Average hit: 1 in 1,453,488 spins.

### 💰 Progressive Jackpot

Trigger: 1 in 10,000 spins. Average jackpot grows with play.

### 🎲 Gamble Feature

After any win, gamble to double or sextuple your win:

- SMALL (1,2,3) or BIG (4,5,6) → ×2
- EVEN (2,4,6) or ODD (1,3,5) → ×2
- NUMBER (pick 1-6) → ×6

## 🧮 Verification

All RTP values verified via 1,000,000,000 (1B) spin Monte Carlo simulation.

| Component | Theoretical | Simulated |
|-----------|-------------|-----------|
| Base RTP × Spin Mult | 91.576% | 91.56% |
| Jackpot RTP | 3.200% | 3.168% |
| Night Creatures RTP | 1.067% | 1.061% |
| Darkest Symbols RTP | 0.110% | 0.321% |
| **TOTAL RTP** | **95.953%** | **96.109%** |

## 🎯 Key Features

- Mathematically verified with 1B spin simulation
- Exact RTP: 96.0%
- Progressive jackpot (1 in 10,000)
- Collection bonuses (Night Creatures + Darkest Symbols)
- Sequential multipliers rewarding winning streaks
- Gamble feature for risk vs reward
- Procedural background music and SFX
- Save/Load via localStorage
- Responsive design for mobile and desktop
- No dependencies — pure HTML/JS/CSS

## 🚀 How to Play

1. Open the demo link above
2. Choose your bet
3. Press SPIN (or AUTO for auto-spins)
4. Watch for sequential multipliers on winning streaks
5. Collect all Night Creatures or both Darkest Symbols for bonuses
6. Trigger the Jackpot
7. Use GAMBLE after a win to risk it for more

## 📜 License

MIT License — free to use, modify, and distribute.

## 🙏 Credits

Game design, math, and code: Dinko Trendafilov

Built with ❤️ and a lot of Monte Carlo simulations.
