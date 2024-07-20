## 介绍

C2服务器部分整体流程基于Havoc C2，使用Go编写，服务器和客户端的通信部分使用Grpc，服务器和Agent的通信部分中对加密算法进行修改。

C2客户端部分使用C#编写，参考SharpC2并对SharpC2进行扩充。

C2 Implant部分使用C和汇编编写，参考了Havoc C2，修改的部分包括：编译时计算哈希值、扩充休眠加密的方式、修改加密算法、间接系统调用的方式等。

##　功能展示

界面

![登录](https://github.com/user-attachments/assets/ccd90c91-b63e-4c3e-a924-87597189bf07)

编译

![编译exe](https://github.com/user-attachments/assets/721c9944-72a9-4de9-89fe-46c4a90fd47c)

![编译dll](https://github.com/user-attachments/assets/a0e74973-6bc6-4ecd-935b-3d0c7007a538)

监听器

![listener创建](https://github.com/user-attachments/assets/8ab6a51c-99ef-4aeb-ac94-6b6a4493bc0a)

![listener删除](https://github.com/user-attachments/assets/e4a7623b-d07e-4c8b-899d-0ee0895fc41b)

上线

![exe上线](https://github.com/user-attachments/assets/ba193328-6dc7-4cce-9b6f-a9a505f3d2b1)

![dll](https://github.com/user-attachments/assets/68f7407b-69a9-4833-8d1f-8391a963faa1)
