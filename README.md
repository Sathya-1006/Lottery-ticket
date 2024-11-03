# Lottery Ticket Simulator

## Overview
The Lottery Ticket Simulator is a console-based application written in C that allows users to experience the excitement of participating in a lottery. Users can input their names, specify the number of lottery tickets they own, and enter their ticket numbers. The program then checks these tickets against a set of predefined winning numbers and provides feedback on their results.

## Features
- **User Input**: Prompts users for their name and the number of tickets they wish to enter.
- **Ticket Validation**: Ensures that all entered ticket numbers are valid 4-digit numbers.
- **Winning Check**: Compares user ticket numbers against multiple predefined winning numbers.
- **Personalized Output**: Displays congratulatory messages for winners, including the prize amount.
- **Total Winnings Summary**: At the end of the session, users receive a summary of their total winnings.

## Usage
1. Compile the program using a C compiler (e.g., `gcc`).
2. Run the executable.
3. Follow the prompts to enter your name and ticket information.
4. View results and total winnings.

## Code Structure
- **`struct Details`**: A structure to hold user information, including name, ticket numbers, and ticket count.
- **`lottery` function**: Manages the main logic for entering ticket numbers and determining winnings.
- **`isWinningTicket` function**: Checks if a given ticket number matches any of the winning numbers.

## Contribution
Feel free to fork the repository, make improvements, or suggest features. Contributions are welcome!
