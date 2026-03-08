# Systemd Service Management

## Introduction
Systemd is the service manager used in most modern Linux distributions. It controls how services start, stop, and run in the background.

## Managing Services

Start a service

systemctl start service-name

Stop a service

systemctl stop service-name

Restart a service

systemctl restart service-name

Check service status

systemctl status service-name

## Enable or Disable Services

Enable service at boot

systemctl enable service-name

Disable service

systemctl disable service-name

## View Services

List running services

systemctl list-units --type=service

View failed services

systemctl --failed

## Logs for Services

journalctl -u service-name

## Conclusion
Understanding systemd services is important for managing applications and background services on Linux servers.
