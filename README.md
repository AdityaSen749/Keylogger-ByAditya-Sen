# Keylogger-ByAditya-Sen
# Node Keylogger

A simple Node.js keylogger using event emitters and global keyboard listener.

## Features

- Logs all key presses to a file (`keylog.txt`)
- Emits events for `keydown`, `keyup`, and `keypress`
![README md - keylogger-main - Visual Studio Code 14-06-2025 20_20_31](https://github.com/user-attachments/assets/b7a660ed-c756-478d-8a6a-043a2fbbd608)
![keylog txt - keylogger-main - Visual Studio Code 14-06-2025 20_17_36](https://github.com/user-attachments/assets/1888a972-5005-4aeb-a2c9-af7e3f7af0cd)


## Getting Started

### 1. open the folder keylogger main in the VSCODE,ensuring that it includes every files that has been provided over here


### 2. Install Dependencies

```sh
npm install
```

### 3. Run the Keylogger

To start logging key presses:

```sh
node keylogger.js
```

All key presses will be logged to `keylog.txt` in the project directory.

### 4. View Logged Keys

Open `keylog.txt` to see the recorded key presses and timestamps.

