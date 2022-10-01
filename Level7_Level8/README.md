# Level 7 -> Level 8
>The password for the next level is stored in the file data.txt next to the word millionth

Dùng password `z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S` để truy cập vào bandit7

Dùng `ls` thì ta thấy được 1 file `data.txt`. Mở file thì ta nhận được các chuỗi khác nhau

![level7_8_1](level7_8_1.png)

Ta dùng lệnh `cat data.txt|grep millionth` để tìm kiếm từ khóa `millionth` trong file thì ta tìm thấy kèm với password

![level7_8_2](level7_8_2.png)

Password cần tìm là: `TESKZC0XvTetK0S9xNwm25STk5iWrBvP`
