# Package Management in Linux

## Introduction
Package management allows administrators to install, update, remove, and manage software packages on Linux systems.

Different Linux distributions use different package managers.

## Common Package Managers

### APT
Used in Debian and Ubuntu based systems.

### YUM / DNF
Used in RedHat, CentOS, and Fedora systems.

### Zypper
Used in SUSE based systems.

## Installing Packages
apt install package-name  
dnf install package-name  

## Updating Packages
apt update  
apt upgrade  
dnf update  

## Removing Packages
apt remove package-name  
dnf remove package-name  

## Searching Packages
apt search package-name  
dnf search package-name  

## Viewing Installed Packages
dpkg -l  
rpm -qa  

## Conclusion
Package management is essential for maintaining system software and keeping systems updated with security patches.
