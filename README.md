# LogClient

LogClient is designed by Okan DÜZYEL for logging internet connection status and program activities on individual computers during lab sections. It is meant for students, and each installation requires a unique registration based on the computer's MAC address.

## Features
- Requires one-time registration for each computer **using a unique activation code.**
- Logs internet connection status (Connected/Disconnected).
- Program records activities and timestamps **with cryptographic output.**

## Registration and Activation (macOS, Linux, and Windows)

1. **First Run:**
    - This error will be appeared on the first run. You must allow the program as **Settings -> Privacy & Security -> LogClient Allow.**
      
      <img width="328" alt="Screenshot 2024-02-29 at 16 38 08" src="https://github.com/okanduzyel/LogClient/assets/38145537/6e8e6135-045b-44c2-a94c-43bdc1f40e75">

    - If you allow correctly the program, the program displays the MAC address of your computer. 

      <img width="724" alt="Screenshot 2024-02-29 at 16 11 07" src="https://github.com/okanduzyel/LogClient/assets/38145537/fb8d2c1d-f099-43cc-b477-1b7c342251f7">

3. **Registration:**
    - The student should send its MAC address and student number to the Assistant via Microsoft Teams.
    - The Assistant provides a unique activation code to the student.

4. **Activation:**
    - Students enter their student number and the provided activation code.
    - The program creates a `license.dat` file for future use.
  
      <img width="731" alt="Screenshot 2024-02-29 at 16 16 49" src="https://github.com/okanduzyel/LogClient/assets/38145537/d325f96f-acb2-43f8-bc03-463857750317">
      
    - If the student give wrong Mac address or wrong student number the program will recognize that and create the output as below. 
  
      <img width="682" alt="Screenshot 2024-02-29 at 16 21 56" src="https://github.com/okanduzyel/LogClient/assets/38145537/5d1bbe8d-eac2-4fcc-be5f-14121575abed">

## Usage

Once registered and activated, the program continuously logs internet connection status and program activities. It runs in the background and requires no further interaction from the user.

1. **For macOS**

- Extract the zip file in your user directory, for example, "/Users/XXXXXXXXXX" (replace XXXXXXXXXX with your username). Please avoid using another directory.
  
   <img width="420" alt="Screenshot 2024-02-29 at 16 34 22" src="https://github.com/okanduzyel/LogClient/assets/38145537/26a049de-076d-43b0-8edd-692f37f0aa1b">

- The `license.dat` file will be automatically created during the extraction process.

- While the program is running, it will generate a new log file named with the student number, day, month, and year.

2. **For Linux**

3. **For Windows**

- Extract the zip file in your user directory, for example, "C:\Users\MyName\Desktop\" (replace MyName with your username). Please avoid using another directory.

   ![WhatsApp Image 2024-02-29 at 16 20 58](https://github.com/okanduzyel/LogClient/assets/38145537/3fabe2be-123c-475e-918a-3c2e97757246)

- The `license.dat` file will be automatically created during the extraction process.

- While the program is running, it will generate a new log file named with the student number, day, month, and year.

## Instructions for Students

Before lab time:

1. Close your internet connection (Wi-Fi, Ethernet, Bluetooh etc.) before running LogClient.
2. Open LogClient.
3. Do not close LabClient, and do not try to connect internet during lab section.
4. After getting grade of the lab, close LogClient, connect internet, and upload your .c file and your log file to Microsoft Teams Assignments section. 
