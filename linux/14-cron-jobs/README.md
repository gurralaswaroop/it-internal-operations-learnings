# Cron Jobs in Linux

## Introduction
Cron is a time-based job scheduler used to automate repetitive tasks such as backups, monitoring scripts, and system maintenance.

## Managing Cron Jobs

View existing cron jobs

crontab -l

Edit cron jobs

crontab -e

Remove cron jobs

crontab -r

## Cron Syntax

* * * * * command

Fields represent:

Minute
Hour
Day of Month
Month
Day of Week

## Example Cron Jobs

Run script every day at 2 AM

0 2 * * * /home/user/backup.sh

Run command every 5 minutes

*/5 * * * * command

## Conclusion
Cron automation is widely used in system administration for scheduled operations.
