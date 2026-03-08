# Log Analysis in Linux

## Introduction
Logs provide information about system activities, errors, authentication events, and application behavior.

Log analysis is critical for troubleshooting and security monitoring.

## Important Log Locations

/var/log/syslog – General system logs

/var/log/auth.log – Authentication and login activity

/var/log/kern.log – Kernel logs

/var/log/dmesg – Boot and kernel messages

## Viewing Logs

cat /var/log/syslog

less /var/log/syslog

## Monitoring Logs in Real Time

tail -f /var/log/syslog

journalctl -f

## Searching Logs

grep "error" /var/log/syslog

grep "failed" /var/log/auth.log

## Kernel Logs

dmesg | tail

## Conclusion
Logs are one of the most important sources for diagnosing system issues and investigating incidents.
