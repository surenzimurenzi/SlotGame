# Slot Machine Game

A simple slot machine game implemented in Python. This game allows players to deposit money, place bets, and spin the slot machine to try their luck at winning.

## Features

- Deposit money to play.
- Bet on up to 3 lines.
- Adjustable bet amounts within a specified range.
- Realistic slot machine symbols (emojis).
- Easy-to-win configuration for an enjoyable experience.

## Symbols and Values

The slot machine uses the following symbols and their corresponding values:

- 🍒: 5 points
- 🍋: 4 points
- 🍉: 3 points
- ⭐: 2 points

## How to Play

1. **Deposit Money**: Start by depositing an amount of money to play with.
2. **Place Bets**: Choose the number of lines (1-3) to bet on and the bet amount for each line.
3. **Spin the Slot Machine**: Spin the slot machine to see if you win. The game will check for winning lines and calculate your winnings.
4. **Continue or Quit**: You can continue playing as long as you have money or quit the game.

## How the game looks
Winning Example:

![image](https://github.com/user-attachments/assets/c0f28bd1-b92a-452a-89dd-64df32b50337)

Losing Example:

![image](https://github.com/user-attachments/assets/1fa32078-a7dd-485c-b564-5a5c2c4a674c)



## Code Structure

- `MAX_LINES`, `MAX_BET`, `MIN_BET`: Constants defining the game rules.
- `ROWS`, `COLS`: Dimensions of the slot machine.
- `symbol_count`: Dictionary defining the number of each symbol in the slot machine.
- `symbol_value`: Dictionary defining the value of each symbol.
- `check_winnings(columns, lines, bet, values)`: Function to check winnings and return the total winnings and winning lines.
- `get_slot_machine_spin(rows, cols, symbols)`: Function to simulate a slot machine spin and return the resulting columns.
- `print_slot_machine(columns)`: Function to print the slot machine layout.
- `deposit()`: Function to handle money deposit.
- `get_number_of_lines()`: Function to get the number of lines to bet on.
- `get_bet()`: Function to get the bet amount for each line.
- `spin(balance)`: Function to handle a single spin of the slot machine.
- `main()`: Main function to run the game.

## How to Run

1. Make sure you have Python installed on your system.
2. Clone the repository to your local machine.
3. Navigate to the project directory.
4. Run the script using the following command:

```bash
python main.py
