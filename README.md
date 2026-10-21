# Shell Scripts

Shell script exercises (1 to 20) for the Operating Systems and Networks course at Fatec (Software Development, 1st semester).

Each script is an interactive menu in the terminal that practices common Linux commands, such as file handling, users, permissions, processes and system information.

## Exercises

| Script | Description | Main commands |
|---|---|---|
| `ex01.sh` | Calculator (sum, subtraction, multiplication, division) | `read`, `bc` |
| `ex02.sh` | Create and remove files | `touch`, `rm` |
| `ex03.sh` | Create and rename files | `touch`, `mv` |
| `ex04.sh` | Create directories and move files between them | `mkdir`, `mv`, `ls` |
| `ex05.sh` | Check if a user exists on the system | `grep`, `/etc/passwd` |
| `ex06.sh` | Search for a word in a file | `grep` |
| `ex07.sh` | Search for files and commands | `find`, `whereis`, `locate` |
| `ex08.sh` | Concatenate files (overwrite or append) | `cat`, `>`, `>>` |
| `ex09.sh` | Compare files | `diff` |
| `ex10.sh` | Show user information (home directory and disk usage) | `getent`, `cut`, `du` |
| `ex11.sh` | List logged-in users | `who` |
| `ex12.sh` | Change file permissions | `chmod` |
| `ex13.sh` | List running processes | `ps` |
| `ex14.sh` | Search for a running process by name | `ps`, `grep` |
| `ex15.sh` | Create, list and kill processes | `sleep`, `ps`, `kill` |
| `ex16.sh` | Kernel and system information | `uname` |
| `ex17.sh` | Count lines, words and characters in a file | `wc` |
| `ex18.sh` | System information panel (date, kernel, calendar, uptime) | `date`, `uname`, `cal`, `uptime` |
| `ex19.sh` | System information menu | `date`, `uname`, `cal`, `uptime`, `who`, `ps` |
| `ex20.sh` | File management menu | `find`, `grep`, `mv`, `rm`, `diff` |

## How to run

    git clone https://github.com/ncsf01/shell-scripts.git
    cd shell-scripts
    bash ex01.sh

Some scripts create test files in the current folder (such as `exemplo.txt` and `doc1.txt`). That is why these files are part of the repository.

## Built with

- Bash
- Linux
