# Cross-OS-Command-Line-Correspondence
Here's a table summarizing some of the most important command line commands in Windows, macOS, and Linux:


| Command              | Windows                 | macOS             | Linux                |
|----------------------|-------------------------|------------------|----------------------|
| List files           | `dir`                   | `ls`             | `ls`                 |
| Change directory     | `cd`                    | `cd`             | `cd`                 |
| Print working directory | `cd` (without arguments) | `pwd`        | `pwd`                |
| Create directory     | `mkdir`                 | `mkdir`          | `mkdir`              |
| Remove directory     | `rmdir`                 | `rmdir`          | `rmdir` or `rm -r`   |
| Copy file or directory | `copy` or `xcopy`     | `cp`             | `cp`                 |
| Move or rename file or directory | `move` or `ren` | `mv`        | `mv`                |
| Remove file          | `del`                   | `rm`             | `rm`                 |
| Display file contents | `type`                 | `cat`            | `cat`                |
| Edit file            | `notepad` or `edit`     | `nano` or `vim` | `nano` or `vim`      |
| Display IP address   | `ipconfig` or `ipconfig/all` | `ifconfig` | `ifconfig`         |
| Ping                 | `ping`                  | `ping`           | `ping`               |
| SSH                  | `ssh`                   | `ssh`            | `ssh`                |
| Search files or text | `dir` or `find`         | `find`           | `find` or `grep`     |
| System information   | `systeminfo`            | `system_profiler` | `lscpu` or `uname` |
| Show running processes | `tasklist`             | `ps`             | `ps`                 |
| Kill a process        | `taskkill`             | `kill`           | `kill`               |
| Display network connections | `netstat`       | `netstat`        | `netstat`            |
| Display disk usage    | `dir /s` or `tree`     | `du` or `df`     | `du` or `df`         |
| Display system uptime | `systeminfo`          | `uptime`         | `uptime` or `w`      |
| Create a symbolic link | `mklink /d` or `mklink /h` | `ln -s`      | `ln -s`             |
| Change file permissions | `icacls`           | `chmod`          | `chmod`              |
| Show system information | `systeminfo`        | `system_profiler` | `lshw` or `lsblk`    |
| Show available memory | `wmic memorychip list full` | `top`      | `free -m` or `top`   |
| Create a compressed archive | `compact` or `zip` | `zip` or `tar` | `tar`                |
| Extract a compressed archive | `compact /u` or `unzip` | `unzip` or `tar -xf` | `tar -xf`        |
| Rename multiple files | `ren *.* *.txt`      | `for i in *; do mv "$i" "${i%.*}.txt"; done` | `for i in *; do mv "$i" "${i%.*}.txt"; done` |
| Set environment variable | `set` or `setx` | `export` | `export` |
| Display system information | `systeminfo` | `system_profiler` | `lshw` or `lsblk` |
| Display available disk space | `fsutil volume diskfree` or `dir` | `df` | `df` |
| Change file ownership | `takeown` or `icacls` | `sudo chown` | `sudo chown` |
| Change file permissions | `icacls` | `chmod` | `chmod` |
| Display running services | `sc query` | `launchctl list` | `systemctl list-units` |
| Start a service | `sc start` | `launchctl start` | `systemctl start` |
| Stop a service | `sc stop` | `launchctl stop` | `systemctl stop` |
| Restart a service | `sc stop` and `sc start` | `launchctl stop` and `launchctl start` | `systemctl restart` |
| Show active network interfaces | `ipconfig` | `ifconfig` | `ifconfig` |
| Change IP address | `netsh interface ipv4 set address` | `sudo ifconfig` or `sudo ipconfig set` | `sudo ifconfig` or `sudo ip addr add` |
| Configure firewall | `netsh advfirewall` | `sudo pfctl` | `sudo ufw` or `sudo iptables` |

