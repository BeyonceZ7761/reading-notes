#  The Coders Computer 

- What are four important features to look for in a text editor?
1.Stream editors
2.Multiple Window Editor
3.DOS-Editor
4.Word Processor
5.Full Screen Editors

- What do the following commands do?
1. pwd- Print working directory  command, exploring its functionality, usage, and various examples. It prints the path of the working directory, starting from the root
2. ls - An interconnected set of components used to collect, store, process and transmit data and digital information
3. cd -  A storage device in the form of small plastic discs which store and retrieve computer data or music using light
4. mkdir - mkdir {dir} (replace {dir} with the desired name of your directory). Before creating any directory or file, remember that most Linux filesystems are case-sensitive
5. touch - command is a standard command used in the UNIX/Linux operating system which is used to create, change and modify the timestamps of a file

- Can you explain what is happening in the following scenario if these commands and arguments are entered into the command line?
1. cd projects - How to do the cd command?
The cd command allows you to move between directories. The cd command takes an argument, usually the name of the folder you want to move to, so the full command is cd your-directory . Now that we moved to your Desktop, you can type ls again, then cd into it. We have just changed into a new directory.

2. mkdir new-project - How do I create a mkdir command?
The basic syntax for using this command is mkdir {dir} (replace {dir} with the desired name of your directory). Before creating any directory or file, remember that most Linux filesystems are case-sensitive.

3.touch new-project/newfile.md -	
The touch command is the easiest way to create new, empty files. It is also used to change the timestamps (i.e., dates and times of the most recent access and modification) on existing files and directories.
touch's syntax is
touch [option] file_name(s)
When used without any options, touch creates new files for any file names that are provided as arguments (i.e., input data) if files with such names do not already exist. Touch can create any number of files simultaneously.
Thus, for example, the following command would create three new, empty files named file1, file2 and file3:
touch file1 file2 file3
A nice feature of touch is that, in contrast to some commands such as cp (which is used to copy files and directories) and mv (which is used to move or rename files and directories), it does not automatically overwrite (i.e., erase the contents of) existing files with the same name. Rather, it merely changes the last access times for such files to the current time.
Several of touch's options are specifically designed to allow the user to change the timestamps for files. For example, the -a option changes only the access time, while the -m option changes only the modification time.

 4. cd.. - The cd command, also known as chdir ( ch ange dir ectory), is a command-line shell command used to change the current working directory in various operating systems. It can be used in shell scripts and batch files.

5. ls projects/new-project - oc new-project myproject --display-name 'My Project'
Already on project "myproject" on server "https://localhost:8443".com
