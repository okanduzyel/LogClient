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
      
      <img width="724" alt="Screenshot 2024-02-29 at 16 11 07" src="https://github.com/okanduzyel/LogClient/assets/38145537/fb8d2c1d-f099-43cc-b477-1b7c342251f7">

2. **Registration:**
    - Students send their MAC address and student number to the teacher via Microsoft Teams.
    - The teacher provides a unique activation code to the student.

3. **Activation:**
    - Students enter their student number and the provided activation code.
    - The program creates a `license.dat` file for future use.
  
      <img width="731" alt="Screenshot 2024-02-29 at 16 16 49" src="https://github.com/okanduzyel/LogClient/assets/38145537/d325f96f-acb2-43f8-bc03-463857750317">
      
    - If you give wrong Mac address or wrong student number the program will recognize that and create the output as below.
  
      <img width="682" alt="Screenshot 2024-02-29 at 16 21 56" src="https://github.com/okanduzyel/LogClient/assets/38145537/5d1bbe8d-eac2-4fcc-be5f-14121575abed">

## Usage

Once registered and activated, the program continuously logs internet connection status and program activities. It runs in the background and requires no further interaction from the user.

1. **For macOS**

- Extract the zip file in your user directory, for example, "/Users/XXXXXXXXXX" (replace XXXXXXXXXX with your username). Please avoid using another directory.

   <img width="408" alt="Screenshot 2024-02-29 at 16 02 42" src="https://github.com/okanduzyel/LogClient/assets/38145537/ab7370b2-24db-452d-a39c-8cdcaa812235">

- The `license.dat` file will be automatically created during the extraction process.

- While the program is running, it will generate a new log file named with the student number, day, month, and year.

Feel free to adjust the instructions based on the specific details of your program and directory structure.

2. **For Linux**

3. **For Windows**



## Requirements

- Python 3.x
- Dependencies: See `requirements.txt`
