---
title:Windows定时关机指令 
categories: [Notes]
comments: true
---

## Windows 定时关机指令

### 设定定时关机
```bash
shutdown /s /f /t <秒数>
```
- /s：表示关机。
- /f：强制关闭正在运行的程序，不会显示提示。
- /t <秒数>：指定关机的时间，单位是秒。例如，3600 秒为 1 小时。

### 取消定时关机
```bash
shutdown /a
```