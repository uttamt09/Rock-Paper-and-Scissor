#include <iostream>
#include <ctime>
using namespace std;

int main() {
    // Seed the random number generator with the current time
    srand(static_cast<unsigned int>(time(0)));

    // Declare variables
    int playerChoice, computerChoice;

    // Display menu
    cout << "Let's play Rock-Paper-Scissors!\n";
    cout << "1. Rock\n2. Paper\n3. Scissors\n";
    cout << "Enter your choice (1/2/3): ";
    cin >> playerChoice;

    // Generate computer's choice (random number between 1 and 3)
    computerChoice = rand() % 3 + 1;

    // Determine the winner
    cout << "\nYou chose ";
    switch (playerChoice) {
        case 1:
            cout << "Rock";
            break;
        case 2:
            cout << "Paper";
            break;
        case 3:
            cout << "Scissors";
            break;
        default:
            cout << "Invalid choice";
            return 1;
    }

    cout << " and the computer chose ";
    switch (computerChoice) {
        case 1:
            cout << "Rock";
            break;
        case 2:
            cout << "Paper";
            break;
        case 3:
            cout << "Scissors";
            break;
    }

    cout << "\n";

    // Determine the winner
    if (playerChoice == computerChoice) {
        cout << "It's a tie!\n";
    } else if ((playerChoice == 1 && computerChoice == 3) || (playerChoice == 2 && computerChoice == 1) || (playerChoice == 3 && computerChoice == 2)) {
        cout << "Congratulations! You win!\n";
    } else {
        cout << "Sorry, the computer wins!\n";
    }

    return 0;
}

