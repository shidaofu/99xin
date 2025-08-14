# 99新
一款CTF工具

​		先叠个甲非专业开发，非全职，开发的初衷就是为了使用方便顺手。如果大家在使用中有什么好的想法或者工具的bug可以在这个【腾讯文档】https://docs.qq.com/sheet/DYm5IekJQaEdzRnBL
填写，如果我有时间并且有能力解决我会去解决。

PS：最后感谢Jason师傅的帮助。

# 功能简介

## 文本处理模块
<img width="810" height="426" alt="image" src="https://github.com/user-attachments/assets/7f6b5419-8240-4549-a0f2-1b83f8695fcf" />

## 图片处理模块
<img width="806" height="295" alt="image" src="https://github.com/user-attachments/assets/09e66813-22ee-4717-96e0-fc71a0ab3456" />

## 字符处理模块
<img width="804" height="779" alt="image" src="https://github.com/user-attachments/assets/e3f5c941-f14c-4fbf-a951-25780b828c40" />

# AWD模块

## 信息收集
<img width="800" height="780" alt="image" src="https://github.com/user-attachments/assets/fa9f29b4-f93b-4fb9-a4ca-5f577bbd4c9a" />

## 防护
<img width="1160" height="946" alt="image" src="https://github.com/user-attachments/assets/93b67863-5bae-4dde-ac60-0e02fec5adf3" />

## webshell利用
<img width="1414" height="465" alt="image" src="https://github.com/user-attachments/assets/53242a40-0fb2-419e-b377-6208fe6437c3" />
<img width="1408" height="490" alt="image" src="https://github.com/user-attachments/assets/5a479567-3074-4fe2-aaaf-9998e55cc159" />

flag文件模块默认执行cat /flag

## 批量提交flag
<img width="814" height="788" alt="image" src="https://github.com/user-attachments/assets/712cf8e3-f7ef-4753-9c6c-3346330a9c9c" />

# 探探模块
<img width="1640" height="785" alt="image" src="https://github.com/user-attachments/assets/6b66554a-e263-4231-98be-5c081d7a1765" />

# 分析模块

## 工控协议解析
<img width="809" height="780" alt="image" src="https://github.com/user-attachments/assets/d6078bb4-65b2-4def-9add-b18c1a896e00" />

## 猜谜语
<img width="819" height="269" alt="image" src="https://github.com/user-attachments/assets/6fbb5d06-e40e-4fae-bd8c-125b2b707cf0" />

## 字符分析
<img width="819" height="534" alt="image" src="https://github.com/user-attachments/assets/fdb39c85-a028-481b-bda8-955791bfb054" />

## 文件分析
<img width="825" height="368" alt="image" src="https://github.com/user-attachments/assets/b37479fa-45b7-442c-876f-98a47e9387ca" />

# webshell流量解密
<img width="635" height="465" alt="image" src="https://github.com/user-attachments/assets/fafe8a24-7e43-45e3-a9e7-f30a7dddeab2" />
<img width="1501" height="1060" alt="image" src="https://github.com/user-attachments/assets/0b346101-1eb8-4a85-9afe-9c1ec1a4d4cc" />
<img width="1505" height="1060" alt="image" src="https://github.com/user-attachments/assets/245e0e70-ba68-4151-90da-c30ceab33259" />
<img width="1155" height="861" alt="image" src="https://github.com/user-attachments/assets/b330ac43-3e20-48bd-8774-e36469dca39e" />
<img width="1175" height="875" alt="image" src="https://github.com/user-attachments/assets/5ff85e4d-bf42-4550-a007-a08104009f6e" />

这里冰蝎jsp这里需要注意的是请求包base64编码了，但是回显包没有，所以这里请求包需要先解密base64在进行16进制编码(记得去除空格)再解密。
<img width="1176" height="330" alt="image" src="https://github.com/user-attachments/assets/cac5acb7-8424-452d-908b-9c12b2170e63" />
<img width="800" height="385" alt="image" src="https://github.com/user-attachments/assets/b282e8df-590b-482d-ae31-18ef4af6523f" />

这里哥斯拉JSP-aes-base，请求包需要手动去除pass=并且需要解URL编码，回显包需要手动删除前后的16位字符串
<img width="800" height="299" alt="image" src="https://github.com/user-attachments/assets/1e4c74bd-3633-483b-9778-0590d5544c7d" />
<img width="814" height="360" alt="image" src="https://github.com/user-attachments/assets/2088c924-c786-43b7-9e02-2e7a10b4bbaf" />

这里哥斯拉-asp-xor-base64，请求包需要手动去除pass=并且需要解URL编码，回显包需要手动删除前后的6位字符串
