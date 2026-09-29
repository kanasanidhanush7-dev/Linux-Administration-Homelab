# Linux Administration Homelab Project

## Project Overview

This project demonstrates hands-on Linux Administration skills using Ubuntu in VirtualBox. The environment was built to simulate real-world system administration tasks and practice user management, permissions, services, storage, networking, troubleshooting, and file sharing.

## Technologies Used

- Ubuntu Linux
- VirtualBox
- OpenSSH
- NFS
- Samba
- LVM
- Git & GitHub
- Linux Users & Groups
- Linux File Permissions
- SGID

## Tasks Performed

### 1. User and Group Management

- Created and managed Linux users
  - `devops`
  - `admin`
- Created the `linuxadmins` group
- Added users to the `linuxadmins` group
- Verified users and group memberships using `id`, `groups`, and `getent`

### 2. File Permissions and Ownership

- Configured user home directories
- Managed file and directory ownership using `chown`
- Configured permissions using `chmod`
- Practiced `750` and `770` permissions
- Verified permissions using `ls -l` and `ls -ld`

### 3. Shared Directory and SGID

Created a shared directory:

```text
/shared
