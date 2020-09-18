A 
Junk File Organizer with Python

1.It is a python program that runs as a command-line tool. Basically, as a lazy  programmer, my desktop or any directory is full of files.

2.Due to a large number of files, it is a daunting task to sit and organize each and every file. It is a Python script that comes in handy and returns a folder “Organiser” where all the files are organized in a well-manner within seconds. It organizes by size(size), last modified date(date), extensions(extension).

B
Main functionality of this code

a)Organize by extension
b)Organize by size
c)Organize by last used date


C
Requirements

I used many built-in libraries like- shutil for file movement,
datetime for get the date of the files,
argparse for the command line parsing and etc.


D
How to use this


For Organize with extension
python main.py --path C:\Users\intel\Desktop\week3day3 --o extension

For organize with size
python file.py --path C:\Users\intel\Desktop\week3day3 --o size

For organize with last used date
python file.py --path C:\Users\intel\Desktop\week3day3 --o date

1. Organize by extension
by using this option user can organize their files by their file extension in a given folder, folder will be created according to file extension and finally all files will be moved to a created folder.

2. Organize by size
by using this option user can organize their files by their file size, according to file sizes random folders will be created and respective files will be moved to them.

3. Organize by Last used/accessed date
by using this option user can organize their files by last used date. random folders will be created according to file's last used date and files will be moved to them.
