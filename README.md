#Add 2 card mạng và cấu hình trên Ubuntu Server 14.04
=======

[Mục lục] (#content)
<ul>
<li> [1. Add thêm card mang trên Ubuntu Server 14.04] (#add)
<li> [2. Cấu hình card mạng trên Ubuntu Server 14.04] (#config)
</ul>

<a name="add"></a>
## 1. Add thêm card mang trên Ubuntu Server 14.04

Để add thêm card mạng cho ubuntu server, ta làm như sau:
**Setting-> add -> new adapter -> card mạng -> OK**
Sau khi add card mạng:

<img src=http://i.imgur.com/MYifQt0.png>

Để xem card mạng, dùng lệnh ``ifconfig -a | grep eth``

<img src=http://i.imgur.com/MYifQt0.png>

Hoặc bạn có thể xem cấu hình card mạng bằng lênh ``ifconfig``

<img src=http://i.imgur.com/VpVRC8v.png>

Dùng lệnh vi /etc/network/interfaces để cấu hình card mạng

<img src=http://i.imgur.com/vR8bhO6.png>



