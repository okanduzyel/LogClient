# LogClient

LogClient is a program designed for logging internet connection status and program activities on individual computers by Okan DÜZYEL. It is meant for students, and each installation requires a unique registration based on the computer's MAC address.

## Features

- Logs internet connection status (Connected/Disconnected).
- Records program activities with timestamps.
- Requires one-time registration for each computer using a unique activation code.

## Registration and Activation (macOS, Windows, and Linux)

1. **First Run:**
    - On the first run, the program displays the MAC address of the computer.
    - Students must run the program only on their personal computers.

2. **Registration:**
    - Students send their MAC address and student number to the teacher via Microsoft Teams.
    - The teacher provides a unique activation code to the student.

3. **Activation:**
    - Students enter their student number and the provided activation code.
    - The program creates a `license.dat` file for future use.

## Usage

Once registered and activated, the program continuously logs internet connection status and program activities. It runs in the background and requires no further interaction from the user.

## Requirements

- Python 3.x
- Dependencies: See `requirements.txt`

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/LogClient.git
   cd LogClient
