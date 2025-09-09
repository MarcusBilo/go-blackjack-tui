# TUI Blackjack

## What is this?

This is a **1v1 blackjack game** where you face off against the dealer using **hole card** rules and **late surrender**, developed using Go and [Bubbletea](https://github.com/charmbracelet/bubbletea). It includes all the main mechanics, but without **splitting** and **insurance**.

### Game Features

- **Adjustable Settings**:
  - Blackjack payout (3:2, 7:5, 6:5)
  - Soft 17 rule (dealer hits or stands on soft 17)
  - Number of decks (1-255), configurable in `strings.json` file
  - Penetration point when to shuffle (0%, 25%, 50%, 75%)
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
5. Enjoy the game!

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

### Game Controls
Once the game is running, simply use your keyboard to navigate through the menus and make your selections.
