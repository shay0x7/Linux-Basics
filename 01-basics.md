# Linux Basics - Essential Commands

## Date & Time Commands

| Command              | Description                              | Example / Note                  |
|----------------------|------------------------------------------|---------------------------------|
| `date`               | Show current date and time               | → To know the time and date     |
| `date +%R`           | Show time only (24-hour format)          | HH:MM                           |
| `date +%x`           | Show date only                           | Localized date format           |

## Calendar

| Command              | Description                              | Example / Note                  |
|----------------------|------------------------------------------|---------------------------------|
| `cal`                | Show calendar of current month           |                                 |
| `cal 2024`           | Show full year calendar                  |                                 |
| `cal 1 2024`         | Show calendar for specific month & year  | January 2024                    |

## Terminal Control

| Command              | Description                              | Alternative                     |
|----------------------|------------------------------------------|---------------------------------|
| `clear`              | Clear the terminal screen                | `Ctrl + L`                      |
| `exit`               | Exit the current shell / session         | `Ctrl + D`                      |

## User Information & Switching

| Command              | Description                              | Note / Effect                           |
|----------------------|------------------------------------------|-----------------------------------------|
| `whoami`             | Print the current logged-in username     |                                         |
| `su - username`      | Switch to another user + load environment| Goes to user's home directory           |
| `su - root`          | Switch to root user (clean login)        | Recommended way to become root          |
| `su root`            | Switch to root (keep current directory)  | Stays in current user's directory       |

## Current Location

| Command              | Description                              | Full form                       |
|----------------------|------------------------------------------|---------------------------------|
| `pwd`                | Print name of current/working directory  | Print Working Directory         |

---

**Quick Reference Table (most used daily)**

- `whoami`  
- `pwd`  
- `date`  
- `clear` / `Ctrl+L`  
- `exit` / `Ctrl+D`
