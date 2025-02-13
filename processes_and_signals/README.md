# Processes and Signals Scripts

This repository contains shell scripts demonstrating process management and signal handling in Linux/Unix systems.

## Scripts Overview

### 0-what-is-my-pid
- Displays the PID (Process ID) of the current script

### 1-list_your_processes
- Shows all running processes for all users
- Displays in a user-oriented hierarchy format
- Includes processes not attached to terminal

### 2-show_your_bash_pid
- Uses `ps` to find and display Bash process PID

### 3-show_your_bash_pid_made_easy
- Uses `pgrep` to find Bash process PID more efficiently

### 4-to_infinity_and_beyond
- Demonstrates an infinite loop process
- Displays "To infinity and beyond" indefinitely

### 5-dont_stop_me_now
- Stops process 4 using `kill` command

### 6-stop_me_if_you_can
- Stops process 4 without using `kill` command

### 7-highlander
- Creates an immortal process that displays text
- Handles SIGTERM signal with a custom message

### 8-beheaded_process
- Kills the process created by script 7

### 67-stop_me_if_you_can
- Advanced version of process termination
- Uses alternate methods to stop infinite processes

## Usage
Each script can be executed directly after making it executable:
```bash
chmod +x script_name
./script_name