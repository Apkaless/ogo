
## Description

This script is a console-based application designed to manage QoS (Quality of Service) policies for games on a Windows system using PowerShell. The application provides a simple interface to list all games in the QoS list, add new games, and remove existing games.

## Features

- **List all games in the QoS list**: Retrieve and display all games currently in the QoS policy.
- **Add a new game**: Add a new game to the QoS policy by providing the game's name and executable file path.
- **Remove a game**: Remove a game from the QoS policy by providing the game's name.

## Requirements

- Python 3.x
- `colorama` library
- `tkinter` library (usually included with Python)
- PowerShell installed on the system

## Installation

1. Clone the repository or download the script.
2. Install the required Python libraries:
    ```bash
    pip install colorama
    ```
3. Ensure you have PowerShell installed and accessible in your system's PATH.

## Usage

1. Follow the on-screen prompts to choose an option:
    - Option 1: Get all games in the QoS list
    - Option 2: Add a new game
    - Option 3: Remove a game

## Functions

- **start()**: Displays the main menu and prompts the user to choose an option.
- **path_validator(path)**: Validates the given path to ensure it points to an executable file.
- **get_powershell_path()**: Retrieves the path to the PowerShell executable.
- **SetNewQosPolicy(rule_name, path)**: Adds a new game to the QoS policy.
- **RemoveQosPolicy(rule_name)**: Removes a game from the QoS policy.
- **GetQosPolicy()**: Retrieves and displays all games in the QoS list.
- **browseFile()**: Opens a file dialog to select a game executable file.

## Example

1. To list all games in the QoS list:
    - Choose option 1.
2. To add a new game:
    - Choose option 2.
    - Enter the game name and select the executable file.
3. To remove a game:
    - Choose option 3.
    - Enter the game name to remove it from the QoS list.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
