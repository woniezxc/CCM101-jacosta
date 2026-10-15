# Laboratory Activity 9: The Cloud Automation Engineer

## Mission Overview
In this final lab mission, I stepped into the role of a Cloud Automation and DevOps Engineer at CloudNova Technologies. The goal was to eliminate manual human errors by building an automated shell script that compresses critical application data and scheduling it to run autonomously every single night using the Linux cron utility.

## Objectives
* Understand the fundamental syntax of Bash shell scripts, variables, and shebang declarations.
* Use the Linux nano text editor to write and save executable code.
* Modify file permissions using the `chmod` command.
* Configure time-based task scheduling using the Linux crontab.
* Document automation workflows and cron expressions accurately in Markdown.
* Complete and finalize my GitHub Cloud Computing Portfolio.

## Commands Executed
* `mkdir app-data` - Created a dummy directory to simulate client data.
* `echo "..." > app-data/data.txt` - Created a test file inside the dummy folder.
* `nano backup.sh` - Opened the terminal text editor to write the automation script.
* `chmod +x backup.sh` - Granted execution permissions to the script file.
* `./backup.sh` - Executed the backup script manually for testing.
* `ls -l backups/` - Verified that the compressed `.tar.gz` backup archive was generated.
* `crontab -l` - Checked active cron jobs.
* `env EDITOR=nano crontab -e` - Opened the crontab table editor to configure the automated schedule.

## Skills Learned
* Writing functional, automated Bash scripts utilizing dynamic variables and timestamped compression.
* Managing Linux file permissions and execution rights safely.
* Setting up automated background schedules with Linux Cron jobs.
* Documenting technical configurations and reflecting on enterprise cloud operations.
