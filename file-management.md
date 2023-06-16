FILE MANAGEMENT
----------------------
 /bin : it contains binary files

/etc : it contains configuration files

/opt : standard dir. to install the 3rd party application.

/root : it is the home dir. for root user.

/home : it is the default dir. in this we will be having files.

/var  : it is the sub-dir of root dir.

/usr : it contains program files

/tmp : temprory files


FILE/ DIR. PERMISSIONS
--------------------------

1. owner ---> who created the file/dir
2. group ----> from which grp owner belongs
3. other user ---> other than owner and group


FILE ACCESS MODE
-------------------

1. read ----> r --> 4
2. write----> w --> 2
3. execute--> x --> 1

d --> dir
rwx ---> owner
r-x ---> grp
r-x --> other user

chmod ----> to set permissions of files or directories.

-rw-r--r--. 1 root     root      0 Apr  6 14:40 file1

chmod 777 file1

7 ---> owner ---> r=4 + w=2 + x=1 = 7
7 ---> group --->
7 ----> other user

file2
--------

owner --> rwx
grp  ---> rw-
other user --> r-x


chmod u=rx,g=r,o=r filename

file <filename>  ---> to see the file type

file * --> to obtain the types of all files of the current dir.



FILE COMPRESSIPON
-------------------------

tar , zip, gzip


tar 
------

it is not a compression command, it will only pull a number of files into one.

syn: tar cvf <filename.tar> <files>

c --> create
v ---> verbose
f  ---> forcefully

to extract
--------------

syn: tar xvf filename.tar


zip 
------
: it is goint to pull the multiple files into one as well as it will reduce the size.

syn: zip file.zip files

to extract
-----------
syn: unzip filename.zip


gzip
-------
it only compress the files
it also compress the file indivisually as well as it can compress the tar/zip files.

syn: gzip filename

to decompress
-----------------
syn: gunzip filename


