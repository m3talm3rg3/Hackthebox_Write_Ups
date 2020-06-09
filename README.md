# Hackthebox_Write_Ups

Writeups for HacktheBox machines and challenges written in Spanish or English.

# Password Protection

Starting with Mazro 2020, HTB flags are dynamic and different for each user, making it difficult to use this flag. So, I have chosen to use the full hash of root.
Therefore you need to have obtained the root flag. 

#### Example.

*cat /etc/shadow*

***Text that you need to get the hash***

root:$6$vb1tLY1qiY$M.1ZCqKtJBxBtZm1gRi8Bbkn39KU0YJW1cuMFzTRANcNKFKR4RmAQVk4rqQQCkaJT6wXqjUkFcA/qNxLyqW.U/:15405:0:99999:7:::

***Obtain the hash***

echo root:$6$vb1tLY1qiY$M.1ZCqKtJBxBtZm1gRi8Bbkn39KU0YJW1cuMFzTRANcNKFKR4RmAQVk4rqQQCkaJT6wXqjUkFcA/qNxLyqW.U/:15405:0:99999:7::: | md5sum
 
Output
151f66db48c6cc1f58c8c20bfc8e705d

***Password***

The output is the password for the wirte up 



__**I hope you find them useful. In case of advice, feel free to contact me.**__
