# SSH (Secure Shell) in Linux

## Introduction
SSH is a secure protocol used to remotely access and manage Linux servers.

It encrypts communication between the client and the server.

## Connecting to a Remote Server

ssh username@server-ip

## SSH Key Authentication

Generate SSH key

ssh-keygen

Copy key to server

ssh-copy-id username@server-ip

## SSH Configuration File

/etc/ssh/sshd_config

This file controls SSH settings such as authentication methods and port numbers.

## Restart SSH Service

systemctl restart ssh

## Conclusion
SSH is the primary method used by administrators to manage remote Linux servers securely.
