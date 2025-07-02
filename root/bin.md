# Commonly Used Linux Commands from `/bin`

This document summarizes the most frequently used Linux commands from the `/bin` directory, categorized for daily use, development, system administration, and general system tools.

---

## 🔧 Everyday Frequently Used Commands

| Command     | Description                        |
|-------------|------------------------------------|
| `ls`        | List files in a directory          |
| `cd`        | Change the current directory       |
| `pwd`       | Show current working directory     |
| `cp`        | Copy files or directories          |
| `mv`        | Move or rename files/directories   |
| `rm`        | Remove files or directories        |
| `mkdir`     | Create new directory               |
| `rmdir`     | Remove empty directory             |
| `cat`       | Concatenate and display file       |
| `less` / `more` | View file content             |
| `echo`      | Print message to console           |
| `man`       | Show manual for a command          |
| `whatis`    | Show brief description of command  |
| `grep`      | Search for patterns in text        |
| `find`      | Locate files in a directory        |
| `chmod`     | Change file permissions            |
| `chown`     | Change file ownership              |
| `top`       | Show running processes             |
| `df`        | Show disk usage                    |
| `du`        | Estimate file space usage          |
| `uname`     | Show system information            |
| `hostname`  | Display system hostname            |
| `ping`      | Check network connectivity         |
| `curl` / `wget` | Download from web             |
| `sudo` / `su` | Run as superuser                |
| `tar` / `gzip` / `xz` | Archive and compress   |
| `nano` / `vi` / `vim` | Text editors in terminal|

---

## 🛠️ Developer and Power User Commands

| Command       | Description                                |
|----------------|--------------------------------------------|
| `gcc` / `g++`  | GNU compilers                              |
| `as` / `ld`    | Assembler and linker                       |
| `make`         | Build automation tool                      |
| `python` / `perl` | Scripting languages                    |
| `jq`           | JSON parser                                |
| `strace`       | Trace system calls and signals             |
| `gdb`          | GNU debugger                              |
| `lsof`         | List open files                            |
| `journalctl`   | Query system logs                          |
| `systemctl`    | Control systemd services                   |
| `ssh` / `scp`  | Secure shell and file copy                 |
| `rsync`        | Efficient file sync                        |
| `awk` / `sed`  | Text processing tools                      |
| `cut` / `sort` / `uniq` | Text filtering & formatting     |
| `diff` / `cmp` | Compare files                              |
| `patch`        | Apply differences to files                 |
| `crontab` / `at` | Task scheduling                         |
| `dnf` / `yum`  | Package management                         |
| `docker` / `podman` | Container management (if installed)  |

---

## 🧠 Less Common But Important Utilities

| Command          | Description                               |
|------------------|-------------------------------------------|
| `tpm2`           | TPM (Trusted Platform Module) tools       |
| `passwd`         | Change user password                      |
| `chage`          | Manage password expiration                |
| `uuidgen`        | Generate unique identifiers               |
| `mktemp`         | Create temporary files                    |
| `uptime`         | System uptime info                        |
| `whoami` / `id`  | Show user info                            |
| `env` / `printenv` | Show environment variables              |
| `watch` / `sleep` / `timeout` | Command timing tools         |
| `mount` / `umount` | Mount or unmount filesystems           |
| `lsblk`          | List block devices                        |
| `kill` / `killall` | Send signals to processes               |
| `renice`         | Adjust process priority                   |

---

## 🔁 Symbolic Links and Aliases

| Alias          | Points To             |
|----------------|-----------------------|
| `awk`          | `gawk`                |
| `sh`           | `bash`                |
| `vi` / `view`  | Vim or `ex`           |
| `man`, `whatis`| Alternatives manager  |
| `yum`          | `dnf-3`               |

---

## 🏁 Summary by Role

- **Regular Users:** `ls`, `cd`, `cp`, `mv`, `cat`, `rm`, `echo`, `man`, `grep`, `chmod`, `sudo`
- **Developers:** `make`, `gcc`, `python`, `git`, `awk`, `sed`, `vim`, `curl`, `diff`
- **Sysadmins:** `systemctl`, `journalctl`, `ssh`, `rsync`, `crontab`, `top`, `df`, `du`, `firewalld`

---

> 📌 Note: Actual availability of tools may vary based on your Linux distribution and installed packages.
