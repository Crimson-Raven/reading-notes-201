# Author: Rebecca Childs
## Reading Notes: 201
### Lab 05

### How can you list the files in the current directory using the command prompt?
you can list all the files in the current directory by typing the `dir` command. You can also move between directories by typing the `cd` command.
### How might the “sfc” command and the “gpupdate” command help in troubleshooting on Windows?
The `sfc` command stands for System File Checker. This command will scan through all of the core operating system files, locate any that may be damaged, and repair any of the damaged files.
If an admin wants to force a certain set of updates after someone has logged in, they can use the `gpupdate` command. This will force a group policy update on the computer. How you would execute this command is as follows, `gpupdate` /target with the name of the computer or user, and then you use /force to force that group policy update. For example: 
`gpupdate /target:anthony`
`/force`
### What advantages does the “robocopy” command offer over the “xcopy” command, and why is it useful for file transfers in certain situations?
`robocopy` is a better version of `xcopy`. This command has the ability to continue a file transfer if it happens to be interrupted in the middle of the task. This can be good for wide area networks or non-terrestrial links where you may not have the most consistent connectivity. 
### Think about any real-life scenarios from your cultural context where the use of command line tools could be beneficial. Describe one such scenario and explain how a specific command line tool would help address the situation.
I’m assuming if you’re having a software issue with your gaming pc, `sfc` would be a good command to use to look at what's going on in the core system files to see if any of them are damaged. `gpupdate` would be used to make sure the group policies are up to date, and if you needed to move over an important file, `robocopy` would be best to use in case the transfer gets interrupted in the middle of moving it. I'm not too fluent in the tech world, so this was the first scenario that came to mind. 
## Things I want to learn more about:
N/A