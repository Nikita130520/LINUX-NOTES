root ---> administrator


USER MANAGEMENT
------------------------
1.GUI
2. CLI
3. modifying the files.


creating users
--------------------

1.useradd : to create a user

syn: useradd username

root user  -----> who has adminitrator priviliges

only root user can create & delete a user, even a root user can login to other user without password.

to verify
-------------
cat /etc/passwd

2. passwd : to set the password for the specific user

syn: passwd username

3. su  : switch user

syn: su username

4. openssl : to encrypt the paasword.

syn: openssl passwd username

5. chage : to know about password
syn: chage -l username


6. userdel : to delete a user.

syn: userdel username

7. disabling the password
--------------------------------

syn: usermod -L username

8. activating the password
--------------------------------

syn: usermod -U <username>


GROUP MANAGEMENT
---------------------
1. groupadd : to create the group.

syn: groupadd grp-name

to verify
--------------
cat /etc/group

user ---> dir. ----> group


2. usermod : to add user to a group.

syn: usermod -a -G grpname username

3. gpasswd -M user1,user2 grpname  : to add multiple user to grp at the same time

4. groupmod  : to change the name of grp.
syn: groupmod -n newname oldname

5. to remove the user from a group:

syn: gpasswd -d username grpname

6. to delete a group 

syn: groupdel grp-name
