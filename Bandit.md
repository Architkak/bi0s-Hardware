# *__"Bandit"__* 

### Level 0

I used ssh command with the username host password and port as
Ssh username@host -p port number 
ssh bandit0@bandit.labs.overthewire.org  -p 2220
Then the password was also bandit0

### Level 1

I used ls -l command to show the files and then cat to see what’s in the readme file where i got the password of the level 1


### Level 2

In this i used cat ./- to view the contents of the file which had password

### Level 3
In this one i used cat “spaces in the filename” to view the password




### Level 4
First i checked the inhere directory and with the ls -a the hidden file was seen after that i used the cat command to see the password


### Level 5
In this I viewed all the files in the inhere directory by using cat./* command

### Level 6
I used find command to find the file of 1033 bytes in size

 ### Level 7
 Here also i used the find command to show the files and then viewed the password by cat command

### Level 8

 In this level the password was stored in the data.txt file. So I viewed the data.txt with the help of cat  commands and the stored data was very large . so by using the cat command with grep i find the password

### Level 9
In this also the password was stored in the data.txt file and the data was large but i used uniq command to find the unique password

### Level 10
In this i viewed the data inside the data.txt with the help of strings command

### Level 11
In this the password was encoded in base64 so first i viewed the password and then decoded it by using base64 -d

### Level 12
In this one first i checked the data.txt by using the cat command and then used rot13 decoder to decode the password 








### Level 13

First I entered into SSH of level 13 then I saw the data inside data.txt . It was in Hex dump format .After that I made a new directory in which I copied data.txt  then used xxd - r  command then I copied it into file 2 .
I checked the file type of file 2 .It was of type gzip then I made a new file of gz format 
After unzipping the gz file I saved it and checked the file type .
The file type  was bzip2 . I made a file.bz2 and unzipped it .Again checked the file type .
The file type  was gzip . I made a file.gz and unzipped it .Again checked the file type .
The file type war tar . I made a file.tar and extracted it and got data5.bin which was also of tar type. 
  After extraction of the tar file I got data6.bin which was a bzip2 file .
I decompressed the bzip2 file and again got the tar file .
After extraction of tar i got data8.bin which was a gzip file.
After unzipping data8.bin finally I got the ASCII text file which was the desired Password.
Simply in this one the password was compressed in different formats i just decompressed it and got the password

### Level 14

This challenge was related to ssh so with the help of ssh and localhost bandit14 was given so i enterned into the next level server


### Level 15

In this one i used the nc command as i was given with the port so by giving the password of the previous level i got the password for this one .



![15](https://user-images.githubusercontent.com/72998453/135269090-9064f287-5bd3-4dcc-901f-4beace284ad9.png)


### Level 16

In this is used openssl command and it was given to us that the port was 30001 and by giving the previous password got the password for the next one.


![16](https://user-images.githubusercontent.com/72998453/135269098-ba47111c-aa4a-47a7-b741-bcac39081a50.png)

![16 2](https://user-images.githubusercontent.com/72998453/135269110-c4c35def-7809-4494-a5f4-3d0adb1075f4.png)






### Level 17

In this level I searched for the ports between 31000 to 32000 and got around 5 open ports. I got into each one then tried to give the previous password but there was only one port containing the password for the next level. So i created a file (bandit17.rsa) and saved the password by using cat command.After giving the permission to access the file i got into the next level.


![17](https://user-images.githubusercontent.com/72998453/135269125-5951ccf2-4277-4616-b1d0-b5b98ef71246.png)

![17 2](https://user-images.githubusercontent.com/72998453/135269130-523f82c6-bbb3-4f31-a608-4d63e29602e4.png)

![17 3](https://user-images.githubusercontent.com/72998453/135269146-1a0cc6e0-7790-44cf-83b2-28fa62858b55.png) 

![17 4](https://user-images.githubusercontent.com/72998453/135269151-bc408e64-61df-4a59-84c3-d84d6f34ff9e.png)

![17 5](https://user-images.githubusercontent.com/72998453/135269153-ef6e3459-489e-4b00-bd90-680ac5a129a3.png)

![17 6](https://user-images.githubusercontent.com/72998453/135269161-54ef1b95-fa80-4088-845e-2ef6c441e1fe.png)

![17 7](https://user-images.githubusercontent.com/72998453/135269167-95ba1a4c-9c27-4171-a096-1a81b3fd46fd.png)






### Level 18

![18](https://user-images.githubusercontent.com/72998453/135252428-2b1aaae5-6b86-493e-9d37-170e9e1a6124.png)

![18 1](https://user-images.githubusercontent.com/72998453/135252422-e3333007-2a4a-4ed1-8112-821db090a9ad.png)

![18 2](https://user-images.githubusercontent.com/72998453/135252414-7ae0c3fe-4f0d-4fb1-83a0-36647cfc56e4.png)



### Level 19

![19](https://user-images.githubusercontent.com/72998453/135252408-9fe2b260-2921-4f33-b33f-ec428635585a.png)
)

![19 1](https://user-images.githubusercontent.com/72998453/135252405-7192aca3-265e-48b8-8c1a-53730e701545.png)

![19 2](https://user-images.githubusercontent.com/72998453/135252402-607f21df-4d77-4006-b328-384d8b75ef3a.png)


### Level 20

![20](https://user-images.githubusercontent.com/72998453/135252396-fd3e876d-4135-490f-959d-af7cb0cbd4da.png)

### Level 21

![21](https://user-images.githubusercontent.com/72998453/135252391-934ccd5f-c086-4d2c-934b-9184ef8e1510.png)

### Level 22

![22](https://user-images.githubusercontent.com/72998453/135252506-87759372-fcff-48ba-a7f0-dec260cdf310.png)

### Level 23




### Level 24


### Level 25



### Level 26



### Level 27



### Level 28




### Level 29


### Level 30



### Level 31




### Level 32




### Level 33

