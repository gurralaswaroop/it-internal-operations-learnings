# systemctl in Linux

## Introduction

`systemctl` is the command-line interface used to interact with **systemd**, the service manager in modern Linux systems.

It allows administrators to manage system services, control system behavior, and monitor service status.

---

# What is systemd

systemd is a system and service manager responsible for:

- initializing the system
- starting services
- managing daemons
- monitoring system state

### Key Features

- Parallel startup of services
- Dependency management
- Resource control using cgroups
- Centralized logging with journal
- Socket-based service activation

---

# Basic systemctl Commands

## Start a Service

```bash
sudo systemctl start apache2
```

Starts a service immediately.

---

## Stop a Service

```bash
sudo systemctl stop apache2
```

Stops the running service.

---

## Enable a Service at Boot

```bash
sudo systemctl enable apache2
```

Ensures the service starts automatically when the system boots.

---

## Disable a Service at Boot

```bash
sudo systemctl disable apache2
```

Prevents the service from starting during boot.

---

## Restart a Service

```bash
sudo systemctl restart apache2
```

Stops and starts the service again.

---

## Reload Configuration

```bash
sudo systemctl reload apache2
```

Reloads service configuration without restarting the service.

---

## Check Service Status

```bash
systemctl status apache2
```

Displays:

- service state
- process ID
- logs and recent activity

---

## List Active Services

```bash
systemctl list-units --type=service
```

Shows all active services currently running on the system.

---

# Conclusion

`systemctl` is a powerful tool used to control and monitor system services in Linux. It simplifies service management and ensures services run correctly and efficiently within the system.

