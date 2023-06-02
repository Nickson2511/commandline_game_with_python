# commandline_game_with_python

Slot Machine Game

This Python script implements a simple slot machine game. The game allows the player to deposit an initial amount of money and spin the slot machine to win or lose money based on the outcome.
Requirements

    Python 3.x

Usage

To play the game, simply run the Python script using a Python interpreter. The script will prompt you to deposit an initial amount, and then you can press Enter to spin the slot machine. Enter "q" at any time to quit the game.
Game Rules

    The game has a predefined number of lines to bet on (maximum of 3).
    Each line can have a bet amount between $1 and $100.
    The slot machine consists of 3 rows and 3 columns.
    The symbols in each column are determined by the predefined symbol counts.
    The player wins money if all symbols in a line are the same.
    The payout is calculated based on the value of the winning symbol and the bet amount.
    The player's balance is updated after each spin.

Functions

    check_winnings(columns, lines, bet, values): Calculates the winnings and winning lines based on the given columns, number of lines, bet amount, and symbol values.
    get_slot_machine_spin(rows, cols, symbols): Generates a random spin of the slot machine based on the number of rows, columns, and symbol counts.
    print_slot_machine(columns): Prints the current state of the slot machine columns.
    deposit(): Prompts the player to enter the initial deposit amount.
    get_number_of_lines(): Prompts the player to enter the number of lines to bet on.
    get_bet(): Prompts the player to enter the bet amount for each line.
    spin(balance): Executes a single spin of the slot machine based on the player's balance.
    main(): The main entry point of the game. Handles the game loop, player interaction, and balance updates.

Constants

    MAX_LINES: The maximum number of lines that can be bet on.
    MAX_BET: The maximum bet amount per line.
    MIN_BET: The minimum bet amount per line.
    ROWS: The number of rows in the slot machine.
    COLS: The number of columns in the slot machine.

How to Play

    Run the script using a Python interpreter.
    Enter the initial deposit amount when prompted.
    Press Enter to spin the slot machine or enter "q" to quit.
    If you win, the winnings will be displayed along with the winning lines.
    Your balance will be updated accordingly.
    Continue spinning or quit the game by entering "q".
    At the end of the game, your final balance will be displayed.

Enjoy playing the slot machine game!
