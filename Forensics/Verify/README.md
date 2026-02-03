# CHALLENGE

![img](1.png)

Lets connect to the target using the username and password over ssh 

![img](2.png)

Lets list and anazyle the files 

![img](3.png)

seems like there is a file folder which contains lot of files , lets use 
command : sha256sum <file_name> to identify the checksum value of the file 

![img](4.png)

The file checksum value should match the checksum.txt file 

![img](5.png)

Lets use command : sha256sum files/* | grep <checksum> 

![img](6.png)

We found the files containing the same value as in checksum.txt

now lets decrupt the file using the code decrypt.sh 

![img](7.png)

We successfully found the flag
