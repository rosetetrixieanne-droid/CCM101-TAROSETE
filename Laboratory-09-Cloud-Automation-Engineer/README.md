

# Laboratory 09: Cloud Automation Engineer

## Mission Overview

This mission demonstrates how Bash scripts and cron
jobs can automate the backup of application data.

## Objectives

- Understand Bash scripting and variables.
- Create an automated backup script.
- Use chmod to allow script execution.
- Schedule daily backups using cron.
- Document the process in Markdown.

## Commands Executed

- `mkdir app-data`
- `echo "This is critical client data." > app-data/data.txt`
- `nano backup.sh`
- `chmod +x backup.sh`
- `./backup.sh`
- `ls -l backups/`
- `crontab -l`
- `env EDITOR=nano crontab -e`

## Skills Learned

- Bash shell scripting
- Linux file permissions
- File compression and backups
- Cron scheduling
- Technical documentation
- GitHub portfolio management
