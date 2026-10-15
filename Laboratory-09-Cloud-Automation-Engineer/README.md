# Laboratory Activity 9: The Cloud Automation Engineer

## Mission Overview
In this final lab mission, I stepped into the role of a Cloud Automation and DevOps Engineer at CloudNova Technologies[cite: 1]. The goal was to eliminate manual human errors by building an automated shell script that compresses critical application data and scheduling it to run autonomously every single night using the Linux cron utility[cite: 2].

## Objectives
* Understand the fundamental syntax of Bash shell scripts, variables, and shebang declarations[cite: 2].
* Use the Linux nano text editor to write and save executable code[cite: 2].
* Modify file permissions using the `chmod` command[cite: 2].
* Configure time-based task scheduling using the Linux crontab[cite: 2].
* Document automation workflows and cron expressions accurately in Markdown[cite: 2].
* Complete and finalize my GitHub Cloud Computing Portfolio[cite: 2].

## Commands Executed
* `mkdir app-data` - Created a dummy directory to simulate client data.
* `echo "..." > app-data/data.txt` - Created a test file inside the dummy folder.
* `nano backup.sh` - Opened the terminal text editor to write the automation script[cite: 3].
* `chmod +x backup.sh` - Granted execution permissions to the script file.
* `./backup.sh` - Executed the backup script manually for testing.
* `ls -l backups/` - Verified that the compressed `.tar.gz` backup archive was generated[cite: 4].
* `crontab -l` - Checked active cron jobs[cite: 4].
* `env EDITOR=nano crontab -e` - Opened the crontab table editor to configure the automated schedule[cite: 4].

## Skills Learned
* Writing functional, automated Bash scripts utilizing dynamic variables and timestamped compression.
* Managing Linux file permissions and execution rights safely.
* Setting up automated background schedules with Linux Cron jobs[cite: 2].
* Documenting technical configurations and reflecting on enterprise cloud operations.
