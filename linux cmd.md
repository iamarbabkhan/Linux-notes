## Linux commands:

1. Create file: `cat file` `touch file` `vi/vim file` `nano file`
* Note: vi/vim and nano is editor
* :w - to save
* :wq or :x - save and quit
* :q - quit
* :q! - force quit
2. Root user: `sudo su`
3. Install package: `sudo apt install packagename`
4. Unistall package: `sudo apt remove packagename`
5. Update package: `sudo apt update`
* Note: su is super user
6. Create a hidden file: `.file`
* Note: "." is used to create hidden file
7. Add text on existing file: `cat >>filename`
8. Merge two file in one: `cat file1 fil2 >filename`
9. list file: `ls` or `ls-l`
10. view file: `cat filename`
11. create directory: `mkdir dirname`
* Note: directory and folder is same
12. Create two directory inside one directory: `mkdir dir/dir1/dir2`
13. Change directory: `cd dirname`
14. Go back one step back from current dir: `cd ..`
15. Print working dir: `pwd`
16. Copy: `cp file1 file2`
* Note: file1 data capied to file2
17. Move: `mv file dir` or `mv file /home/dir`
* Note: file moved to directory
18. Rename: `mv file file1`
* Note: file name change to file1
19. Remove file or dir: `rm file` or `rm dir`
* Note: is command is only for blank file
20. Remove file or dir forcefully: `rm -rf file or dir`
21. System detail: `hostname`
22. Ip address: `ifconfig`
23. Start service: `sudo service packagename start`
24. Stop service: `sudo service packagename stop`
* Note: start or stop software on linux
25. Start service at boot: `sudo chkconfig packagename on`
26. Stop service at boot: `sudo chkconfig packagename off`
* Note: start or stop service automatically during boot
27. Display current user and username: `whoami`
28. Search file or text: `grep filename or text` or `grep filepath like /root/home/user`
29. create user: useradd username
30. Create group: `groupadd name`
31. Add user or multiple user into group: `gpasswd -a/-M`
32. File backup/hardlink: `ln filename backupfilename`
33. Softlink/sortcut: `ln -s filename softfilename`
34. Create tar file: `tar -cvf filename filesource`
* Note: dir/file/file1/file2 
35. Create zip or compress: `gzip filename`
36. Unzip file: `gunzip filename`
37. Extract file: `tar -xvf filename`
38. Download file: `wget url or curl url`
39. Change mode: `chmod 777 filename`
40. Change owner: `chown 777 ownername`
41. Change group: `chgrp 777 groupname`
* Note: r= read(4), w= write(2), x= execute(1)
42. Grant superuser permission: `sudo usermod -aG sudo username`
43. Change user password: `passwd username`
44. List users: `cat /etc/passwd
45. check user privilege: `sudo ls /root`
46. Create tar file: `tar -cvf archive.tar -C /path/to/destination`
47. Extract tar: `tar -xvf archive.tar -C /path/to/destination`
48. Create zip:  `zip -cvf archive.zip -C /path/to/destination`
49. Extract zip: `unzip archive.zip -C /path/to/destination`
* Note: `sudo apt-get install zip unzip`
50. Find file location: `which filename` or `whereis filename`
