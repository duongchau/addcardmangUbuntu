#Add 2 card mạng và cấu hình trên Ubuntu Server 14.04
=======

[Mục lục] (#content)

[1. Add thêm card mang trên Ubuntu Server 14.04] (#add)
 
[2. Cấu hình card mạng trên Ubuntu Server 14.04] (#config)

[3.Lời cảm ơn] (#tks)

<a name="add"></a>
## 1. Add thêm card mang trên Ubuntu Server 14.04

Để add thêm card mạng cho ubuntu server, ta làm như sau:
**Setting-> add -> new adapter -> card mạng -> OK**
Sau khi add card mạng:

<img src=http://i.imgur.com/MYifQt0.png>

<a name="config"></a>
## 2.Cấu hình card mạng trên Ubuntu Server 14.04

Để xem card mạng, dùng lệnh ``ifconfig -a | grep eth``

<img src=http://i.imgur.com/qgxUffa.png>

Hoặc bạn có thể xem cấu hình card mạng bằng lệnh ``ifconfig``

<img src=http://i.imgur.com/VpVRC8v.png>

Dùng lệnh vi /etc/network/interfaces để cấu hình card mạng

<img src=http://i.imgur.com/vR8bhO6.png>

Sau đó bạn restart lại bằng câu lệnh sau :   ``sudo /etc/init.d/networking restart``

Hoàn thành

<a name="tks"></a>
## 3.Lời cảm ơn
Cảm ơn các bạn đã đọc hết bài viết này. Tôi hoan nghênh mọi ý kiến đóng, góp xin hãy post lên blog của tôi hoặc có thể commit lên github này.



