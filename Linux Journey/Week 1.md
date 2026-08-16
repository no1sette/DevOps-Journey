# Week 1

## Day 0

So far my first struggle was getting a free amazon aws account as I've created multiple free accounts over the years.

After that i was able to get an EC2 instance spun up and working, and was able to get a Ubuntu up and running.

Connected, updated and restarted when there was a kernel update.

So far easy day 0.

## Day 1

Was able to connect via SSH through my terminal, faced an issue with the paired key I downloaded. The solution was to modify it by making it a read-only file.
Running `chmod 400 "file.pem"` on your terminal is the fastest way to do that.

Then I ran some commands to get familiar with the system.

`lsb_release -a` for linux distro info

`cat /etc/os-release` for current OS

`uname -a` system information

`whoami` prints your username you logged in with

`uptime` how long its been running for

### Hardware

`lshw` hardware details

`lscpu` cpu architecture

`lsblk` block devices

`lspci` pci devices

`lsusb` usb devices

### Memory and Storage

`free -h` memory left

`vmstat` memory statistics

`dh -h ` disk space

`top` task manager

`htop` prettier task manager

### Networking

`ip config` for network interface

`ip address` for newer simpler version of the network interface

`netstat -i` for static view on the network

`ifstat` for continuous monitoring

`sudo iftop -i ens5` for continuous monitoring on a specific interface

## Day 2

### Basic navigation

On this day I'm learning about documentation and navigation.

### Read The Manual

I previously do know about the `-help` functionality but learning about the `man` has really been intersting, pushes it to a more interactive manual.

Next is `tldr`. I have never used this before, had to install it with `snap install tldr` and it's a pretty cool tool, If you've been on the internet long enough, TLDR is pretty self explanatory.

`apropos` is another interesting comman, imagine a thesauraus but for functions

`mank -k` is another with similar functionality

### Navigation

Now onto navigating around

`pwd` print working directory

`cd` moves to different area

`cd ..` move one folder up

`ls` list the items in the files

### Create and Delete

`mkdir` as you might already know is about creating a directory

`mv` to move to a different path

`rmdir` to dellete directory alternative is `rm -r` if there are still items in that folder

`rm` to delete

`touch` to make empty files, I can imagine if you need to create a log file destination
