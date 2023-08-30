# 20 Must Know Linux Commands

Moving from using operating systems with a graphical user interface to a command line based system like Ubuntu Server can be daunting with having to do everything by typing in commands but by knowing this 20 commands will help greatly.


## 1: sudo

    sudo

The sudo command is used to provide administrative access to run commands that may need it. It gives a 15 minute session that after authenticated, will let the user run administrative tasks or commands that need root permissions.

### Example

    sudo apt update

## 2: cd

The cd command is used to move from one directory to another. It is a very used command so its important to understand how to use it so you can navigate around a linux based machine.

    cd

### Example

    cd /home/user/files

## 3: ls

    ls

The ls commands lists the structure of the directory you are working with, in easier terms, it will show all the files that are in the current directory you are working with as well as with different flags can show more options such as file permissions and more.

### Example

    ls -l

The above command with list the file structure of the directory as well as show the file permissions of them all.

## 4: pwd

    pwd

Pwd shows the present working directory. If you are working in a directory and you want to know the path of where its located you can use this command and it will list out the directory for you.

## 5: cat

    cat

Cat is short for concatenate and is a very useful command as it has multiple uses and be very useful when looking for file content without having to open it.

### Example

    cat file1.txt file2.txt > file3.txt

This command will take the contents of file 1 and file 2 and write them both to file 3.

## 6: cp

    cp

cp is a copy command and also can be used for different purposes like renaming existing files to new ones and more.

### Example

    cp file1.txt file2.txt /home/user/documents

This command will copy file 1 and write it to the document’s directory as file 2

## 7: mv

    mv

Similar to cp mv can also rename files as well as move them to different directories.

### Example

    mv file1.txt file2.txt /home/user/documents

This command will move file1.txt to /home/user/documents and rename it to file2.txt

## 8: mkdir

    mkdir

Mkdir is used to make new directories in the current location you are in. So if you’d like to make a subfolder in a folder this command can be used for it.

### Example

    mkdir myFolder

## 9: rm

The rm command is used to remove a file. It also has different flags that can be used for different uses such as removing a directory and more

    rm myfile.txt

## 10: locate

    locate myfile

The locate command can be used to search a system for a specific file. There are different flags that can be used to help the search narrow down such as adding a directory or wildcards to it.

### Example

    locate myfile /home/user/documents

## 11: grep

    grep

Grep can be used to search for a certain word in files and will output them for you to see without having to read through the whole file for it.

### Example

    grep barmine barmineTech.txt

## 12: df

    df

The df command is used to show the current disk space usage

### Example

    df -h

This command shows the disk usage in a human readable format

## 13: chmod

    chmod

Chmod is used to modify files read, write and execute permissions.

### Example

    chmod 777 myfile.txt

This command gives the file all permissions

## 14: chown

    chown

Chown is used to change ownership of a file or directory

### Example

    chown root myfile.txt

## 15: wget

    wget

Wget is used to download files from the internet over http, https and ftp.

### Example

    wget www.barminetech.com/myfile.zip

## 16: history

    history

History is a very useful command as it can show up to the last 500 commands ran on the system

## 17: man

    man

The man command is used to show the manual for commands that are installed on a system

### Example

    man nmap

This will show the manual for how to use the nmap command

## 18: zip and unzip

    zip
    unzip

These commands are used to zip and unzip archive files

## 19: useradd

    useradd

This command is used to add a user, it will open a wizard that asks for inputs in creating a new user on the system

## 20: passwd

    passwd

This command is used to change the password of the user signed in on a system.
