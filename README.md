# Data Center & IT Home Lab

This repository documents my hands-on training in computer hardware,
Linux, networking, server fundamentals, and technical troubleshooting
as I transition into data center and IT infrastructure operations.

## Current Training

- Linux Fundamentals
- TCP/IP Networking
- Network Troubleshooting
- Computer Hardware
- Server Fundamentals
- Cisco Packet Tracer

## Labs

### Lab 01 — Linux Fundamentals Part 1
Status: Completed

Platform: TryHackMe

Skills practiced:
- Navigating the Linux filesystem with `ls`, `cd`, and `pwd`
- Viewing file contents with `cat`
- Identifying the current user with `whoami`
- Searching for files and text using `find` and `grep`
- Understanding relative directory navigation with `cd ..`
- Chaining commands using `&&`
- Running commands in the background using `&`
- Redirecting command output with `>` and `>>`

Key concepts learned:
- `&&` runs the next command only if the previous command succeeds.
- `&` runs a command in the background.
- `>` redirects output to a file and overwrites existing contents.
- `>>` redirects output to a file and appends instead of overwriting.
- Linux commands operate relative to the current working directory.

### Lab 02 — Linux File Management
Status: Completed

Environment: Ubuntu 24.04 / Killercoda

Skills practiced:
- Creating directories with `mkdir`
- Creating files with `touch`
- Viewing directory contents with `ls`
- Writing file contents using `>`
- Appending file contents using `>>`
- Reading files with `cat`
- Copying files with `cp`
- Moving and renaming files with `mv`
- Organizing files into directories
- Removing files with `rm`

Lab exercise:
Created a simulated server file-management environment, wrote and
appended status information to a file, created a backup copy, moved
the backup into a dedicated directory, renamed files, and removed
unneeded files.

### Lab 03 — Linux Permissions & Executable Files
Status: Completed

Environment: Ubuntu 24.04 / Killercoda

Skills practiced:
- Viewing Linux permissions with `ls -l`
- Understanding read (`r`), write (`w`), and execute (`x`) permissions
- Changing permissions with `chmod`
- Using numeric permissions such as `600` and `644`
- Adding execute permissions with `chmod +x`
- Creating and running a basic shell script
- Troubleshooting a "Permission denied" error

Lab exercise:
Created a shell script, verified that it could not execute without
the proper permission, added execute permission with `chmod +x`,
and successfully ran the script.

### Lab 04 — Physical Computer / Server Lab
Status: Not Started

### CCNA Networking Labs — Jeremy's IT Lab
Status: In Progress

Platform: Cisco Packet Tracer

Currently completing hands-on networking labs as part of CCNA 200-301 training through Jeremy's IT Lab.

Topics and completed lab exercises will be documented here as I progress through the course.
