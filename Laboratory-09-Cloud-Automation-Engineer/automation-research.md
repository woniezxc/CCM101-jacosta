# Automation Research & Concepts

## Bash Script
A Bash script is basically a plain-text file packed with a sequence of terminal commands that the Linux shell runs line-by-line, saving us from typing them out manually. At the very top of the file, the shebang line (`#!/bin/bash`) acts as a pointer telling the operating system exactly which interpreter to use so it knows how to parse and execute the script properly.

## Variables
Programmers use variables (like `$BACKUP_DIR`) instead of hardcoding exact folder paths because it keeps the code flexible and clean. If a directory name changes later on, I only have to update it once at the top of the script rather than hunting down every single line where that path is referenced.

## Cron Job
A cron job is a built-in Linux task scheduler that automatically triggers scripts or commands at set times and dates in the background. It is essential for cloud operations because it completely removes human error and ensures routine background tasks—like critical midnight backups—happen reliably without needing anyone to manually press a button.
