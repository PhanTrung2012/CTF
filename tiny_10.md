đơn giản thì chỉ là chỉnh file bằng HxD

![image](https://github.com/PhanTrung2012/CTF/assets/121162586/ea65dd83-b806-438e-9222-d4165487b490)

mở file trên cyberchef rồi tìm đoạn hex ff c0 00 11 08 00 0a 00 0a

đầu tiên sẽ chỉnh lên 120 x 120
 vẫn không có gì và tiếp tục chỉnh lên tiếp (guessing :v)

 chỉnh thành FF C0 00 11 08 00 A0 00 A0 và chúng ta có flag
 
 ![image](https://github.com/PhanTrung2012/CTF/assets/121162586/9a159b40-d509-4f39-b3aa-67e72aa5d57d)

flag: FLAG{b1g_en0ugh}
