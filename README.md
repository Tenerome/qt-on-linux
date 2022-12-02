# qt-on-linux

x64架构linux系统安装qt creator(opensource-5.14.2)

### 赋权限

```bash
chmod +x qt-opensource-linux-x64-5.14.2.run
```

### 安装

```bash
./qt-opensource-linux-x64-5.14.2.run
```

### 选择qt的开发环境

![](/home/tenerome/.config/marktext/images/0a5bd98c6a3e41f62b0c7d07a57a41721171387b.png)

Desktop gcc 64-bit是必须选的，虽然名字是gcc，但实际是qt专用的开发包（qmake等），其他按需求安装

### 卸载

进入qt安装目录

```bash
./MaintenanceTool
```
