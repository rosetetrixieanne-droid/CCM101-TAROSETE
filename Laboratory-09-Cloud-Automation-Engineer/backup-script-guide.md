
# Backup Script Guide

## 1. Backup Script

The `backup.sh` script automatically compresses the `app-data` directory into a timestamped `.tar.gz` backup file.

### Code

```bash
#!/bin/bash

SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

mkdir -p "$BACKUP_DIR"
tar -czf "$BACKUP_DIR/backup_$TIMESTAMP.tar.gz" "$SOURCE_DIR"

echo "Backup completed successfully at $TIMESTAMP!"
```

### Explanation

- `#!/bin/bash` specifies that the script uses Bash.
- `SOURCE_DIR` defines the directory to back up.
- `BACKUP_DIR` specifies where backup files will be stored.
- `TIMESTAMP` generates the current date and time for the filename.
- `mkdir -p` creates the backup directory if it does not exist.
- `tar -czf` compresses the source directory into a `.tar.gz` file.
- `echo` displays messages indicating the backup process.

## 2. File Permissions

### Command

```bash
chmod +x backup.sh
```

This command adds execute permission to the script so it can be run as a program.

To execute the script manually, use:

```bash
./backup.sh
```

## 3. Cron Schedule

### Cron Expression

```cron
0 2 * * * /root/backup.sh
```

This schedule automatically runs the backup script every day at 2:00 AM.

### Schedule Breakdown

| Field | Value | Description |
|---|---|---|
| Minute | `0` | At minute zero |
| Hour | `2` | At 2:00 AM |
| Day of Month | `*` | Every day |
| Month | `*` | Every month |
| Day of Week | `*` | Every day of the week |

## 4. Configure the Cron Job

Open the root user's crontab:

```bash
crontab -e
```

Add the following line:

```cron
0 2 * * * /root/backup.sh
```

Save the file and exit the editor.

## 5. Verify the Cron Job

Check the scheduled cron jobs:

```bash
crontab -l
```

The output should contain:

```cron
0 2 * * * /root/backup.sh
```

## 6. Verify the Backup Files

List the contents of the backup directory:

```bash
ls -lh backups/
```

To check the contents of a backup archive, use:

```bash
tar -tzf backups/backup_YYYYMMDD_HHMMSS.tar.gz
```

Replace `YYYYMMDD_HHMMSS` with the actual timestamp of your backup file.
