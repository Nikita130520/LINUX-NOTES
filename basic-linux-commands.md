basic linux commands
-------------------------
1. touch : to create an empty file.

syn: touch <filename>

2. mkdir : (make directory) to create directory.

syn: mkdir <directory name>


3. ls : to list out all the files and directories.

syn: ls
syn: ls -l

4. cd : change directory --> to go inside a particular folder.
syn:  cd <dir-name>

syn: cd ..   ---> to come outside a directory.

5. pwd : present working directory

6. whoami: to know the user.

7. cntrl + L/ clear  ----> to clear screen

8. editors
--------------
vi, vim, nano : to edit the text of the files.

1. vi : 

syn: vi <filename>

press I to insert anything

esc + :wq 

w ----> to save
q ----> to quite

2. nano :
syn:  nano <filename>

edit the text

ctrl s + cntr x

cntrl s : to save
cntrl x : to exit


9. cat 
--------

1. cat <filename>  : it will print the content of the file.

2. cat >filename  : it will override the content present in file

3. cat >>filename : to add the content in the file witout overriding


10. cp : copy : to copy the file from one path to another path.

syn:  cp src.dir/filename destination dir.

11. cp -r  : to copy a dir. including all its content from src dir. to dest. dir.

12. mv : move : to move files from one path to another

syn: mv  src-dir/filename dest. dir

13. mv : to rename the directory.

syn: mv <oldname> <new>


14. rm : remove : to delete a file

syn: rm <filename>

15. rmdir : remove directory : to delete an empty directory.

syn: rmdir <dir-name>

16. rm -r : to delete the dir. having sub-dir. inside it.
syn: rm -r <dir-name>

17. rm -rf : to delete directory and files forcefully.
syn: rm -rf < dir/file-name>

18. rm *.<extension>  ---> to delete multiple files having same extension at the same time.

19. echo : to print the content.

syn: echo "messege"


20. cal : calender : to print calender.

syn: cal : it will print present month
syn: cal <year> : it will print whole calender of that specific year.
syn: cal <month> <year> : it will print specified month of the year.

21. date : it will print the date.


 TO KNOW ABOUT SYSTEM INFORMATION
-----------------------------------
uname : it will print the system info.

syn:

uname -o : it will print the o.s
uname -v : to know version
uname -r : about kernel release
uname -m : about machine
uname -a : to print all info. about system.

