# Linux Fundamentals

Linux fundamentals are essential for cybersecurity professionals because
most security tools, servers, and testing environments run on Linux.
Understanding Linux basics helps in system navigation, access control,
software management, and network troubleshooting during security testing
and system administration tasks.

---

## File System Navigation

Linux uses a hierarchical file system structure where everything starts
from the root directory `/`. Efficient navigation of the file system is
important for managing files, logs, tools, and configuration files.

Commonly used commands include:
- `pwd` – Displays the current working directory
- `ls` – Lists files and directories in the current location
- `ls -l` – Displays detailed file information
- `cd` – Changes the current directory

These commands help users quickly locate files and directories while
working with Linux-based security tools.

---

## File & Directory Permissions

Linux controls access to files and directories using permissions and
ownership. Permissions define what actions can be performed on a file.

### Permission Types
- **Read (r)** – View file contents
- **Write (w)** – Modify file contents
- **Execute (x)** – Run the file as a program

Permissions are assigned to:
- Owner
- Group
- Others

Common permission and ownership commands:
- `chmod` – Change file permissions  
  Example: `chmod 755 file.sh`
- `chown` – Change file ownership  
  Example: `chown user:user file.txt`

Proper permission management helps prevent unauthorized access and
privilege misuse.

---

## Package Management

Linux uses package managers to install, update, and manage software.
Proper package management ensures systems remain secure and updated.

Common package management commands:
- `apt update` – Update package list
- `apt upgrade` – Upgrade installed packages
- `apt install <package>` – Install a package
- `dpkg -l` – List installed packages

Package management allows quick installation of security tools and helps
keep systems patched against vulnerabilities.

---

## Networking Commands

Linux provides built-in networking commands to inspect network
configuration and test connectivity.

Common networking commands include:
- `ifconfig` or `ip a` – Display network interfaces and IP addresses
- `ping` – Test connectivity between systems
- `netstat -tuln` – Display open ports and active connections
- `traceroute` – Show the path packets take to reach a destination

These commands are commonly used during reconnaissance, troubleshooting,
and basic network analysis.
