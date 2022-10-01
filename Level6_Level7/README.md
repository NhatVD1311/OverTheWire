# Level 6 -> Level 7

Dùng password `P4L4vucdmLnm8I7Vl7jG1ApGSfjYKqJU` truy cập vào bandit6

Xem thử có thư mục nào ở file hiện hành không thì ta nhận ta không thư mục nào.

![level6_7_1](level6_7_1.png)

Điều đặt ra ở đây là ta cần tìm `file` ở nơi nào đó có yêu cầu `owned by user bandit7, owned by group bandit6, 33 bytes in size`. Ta dùng lệnh `ind / -type f -user bandit7 -group bandit6 -size 33c`. Sau một lúc tìm kiếm thì ta tìm được đường dẫn `/var/lib/dpkg/info/bandit7.password` không bị `Permission denied`

![level6_7_2](level6_7_2.png)

Mở file và ta được password cần tìm

![level6_7_3](level6_7_3.png)

Password cần tìm là: `z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S`
