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
