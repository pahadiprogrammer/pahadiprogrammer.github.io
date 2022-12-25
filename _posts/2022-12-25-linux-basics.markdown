---
layout: post
title: "Linux Basics"
categories: tech
---

### What is Linux
In laymen terms, Linux is an operating system which can be used in place of windows to perform operations on computer devices. 

### How is it different from Unix
Linux and Unix have same underlying code that is linux is derived from unix. But now they are maintained by different entities. Also linux is open-source which means people using it don't need to purchase any license which comes with fee.

### What is the need to learn linux commands
Compared to windows, which comes with a default Graphical User Interface which allows people to visualize the actions performed on computer Linux doesn't have one.

### What's the problem in installing a GUI on Linxu based OS
Devs can do that but it may feel easy. But there is another way of doing things using terminal and using linux commands which if someone gets hang of seems bit faster and reliable. Using linux commands on terminal devs can see what's actual happening on system and easy to debug issues on system too.

### What are the linux commands one should be aware of
There are host of commands which can be read in linux manual but here we will cover basic commands that will be mostly used.

- `pwd`: it gives info to user about present working directoty.
- `ls`: Gives info about all files and directories in current working directory
- `cd <PATH>`: It's Change directory command which will take user to the location corresponding to **PATH** passed
- `mkdir <DIRECTORY_NAME>`: It helps in creating a new directory. In order to create directoty at the location either `cd` to the **PATH** and then use this command - `mkdir <name of directory>` else pass full path beofre directlty name.
- `ssh <hostname>`: It helps user to login to the server corresponding to **hostname** passed. If host is protected then it will prompt for creadentials and then only will allow to access the system.

### Exercise
- Open [link](https://linuxcontainers.org/lxd/try-it/)
  - Check **I have read and I accept the terms of service above.** and click `Start`. 
  - Wait for few seconds before a **Terminal** will appear
  - Execute the below commands in manner mentioned below
- Execute `pwd` 
    - Output: `/root`
- Execute `ls`
    - Output: It will be empty as there are no files or directories at present
- Execute `mkdir test`
    - Output: It will not give any output and will only create a **test** directory
- Execute `ls`
    - Output: will display `test` as that's the only directory present. There is no file pre
- Execute `cd test`
    - Output: No output but will take user to new **test** ddirectory
- Execute `pwd`
    - Output: `/root/test`