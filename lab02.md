# Author: Rebecca Childs
## Reading Notes: 201
### Lab 02

### What is the primary function of a shell in a computer’s operating system?
A shell is a user program that provides an interface for the user to use the operating system services. Shell accepts human commands from the user and converts it into something the kernel can understand. A shell is a command language interpreter that executes commands and reads from input devices such as keyboards or files. The shell starts when the user logs in or starts the terminal.
### How does Bash locate and execute commands on a Linux or Unix system?
Bash will use a shell variable called $PATH to locate your executable commands. The $PATH variable is a list of directories. Those directories are separated by colons (:), and Bash will search each directory for a file with the name that you prompted for. 
### How can you determine if your system is running a Bash shell?
To find out whether you're running a Bash shell, use the echo command along with a special variable that represents the name of the currently running process: `$ echo $0
bash`
### What makes Bash scripting powerful and why is it considered scriptable?
It allows users to execute commands, navigate the file system, and run scripts that can automate repetitive tasks. It also serves as both a powerful command interpreter for direct user interaction, and a scripting language for automating tasks. 
### Bash scripting allows for customization, automation, and efficiency. Discuss methods or practices from your previous work experience or cultural background that aim to achieve similar goals in daily tasks.
Personalization features: Many applications and websites offer personalization features that allow people to customize their experience. For example, you can set preferences for news feeds, language settings, or light themes. This is similar to how bash scripts can tailor actions to specific user needs.
Processing: Many tools allow you to process multiple files or tasks at the same time, saving time and effort. This mirrors scripts that perform bulk operations on groups of files or data.
## Things I want to learn more about:
N/A
