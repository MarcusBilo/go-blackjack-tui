## What is this?

This is a **1v1 blackjack game** where you play against the dealer, with **hole card** and **late surrender** rules. Developed using [Go](https://go.dev) and [Bubbletea](https://github.com/charmbracelet/bubbletea), it includes all the key mechanics of the game, minus **splitting** and **insurance**.

### Game Features

- **Adjustable Settings**:
  - Blackjack payout (3:2, 7:5, 6:5)
  - Soft 17 rule (dealer hits or stands on soft 17)
  - Number of decks (1-255), configurable in `strings.json` file
  - Penetration point, i.e. when to shuffle (0%, 25%, 50%, 75%)
- **Betting Structure**: Bet between 10-50 in increments of 10
- **Starting Bankroll**: Begin with 100
- **Save/Load System**: Continue your session where you left off
- **Language Support**: Customize most text through the `strings.json` file

## How to Play

### Option 1: Download Pre-built (Windows)
1. Go to the **[Releases](../../releases)** page
2. Download the latest `.zip` file
3. Extract the contents to a folder of your choice
4. Run the `.exe` file

### Option 2: Build from Source
1. Make sure you have [Go](https://golang.org/dl/) installed (version 1.25.0 at best)
2. Clone this repository:
   ```bash
   git clone https://github.com/MarcusBilo/go-blackjack-tui
   cd go-blackjack-tui
   ```
3. Build and run:
   ```bash
   go build
   .\go-blackjack-tui
   ```

## Game Controls
Once the game is running, simply use your keyboard to navigate through the menus and make your selections.
