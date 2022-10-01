# Level 13 -> Level 14
> The password for the next level is stored in /etc/bandit_pass/bandit14 and can only be read by user bandit14. For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. Note: localhost is a hostname that refers to the machine you are working on

Dùng password `wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw` để truy cập vào bandit13

Dùng `ls` ta thấy được 1 private key ssh 

![level13_14_1](level13_14_1.png)

Ta dùng lệnh `scp` để download key về máy, sau đó thiết lập cấp quyền read cho user  

![level13_14_2](level13_14_2.png)

Dùng `ssh` truy cập ở local,  sau đó `cat /etc/bandit_pass/bandit14` ta được password

![level13_14_3](level13_14_3.png)

![level13_14_4](level13_14_4.png)

Password cần tìm là: `fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq`


