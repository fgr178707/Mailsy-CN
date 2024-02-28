

# 快速生成一次性电子邮件。
原项目地址 [Mailsy](https://github.com/BalliAsghar/Mailsy)

## 屏幕截图

![alt text](https://raw.githubusercontent.com/BalliAsghar/Mailsy/main/screenshot/Mailsy.png)

## 安装
使用软件包管理器 [npm](https://nodejs.cn/download/) 安装 Mailsy。

```console
npm install mailsy -g
```

Macos 用户可通过自制软件安装 mailsy

```console
brew install mailsy
```

## 使用方法

**创建电子邮件**

电子邮件将复制到剪贴板！

```console
foo@bar:~$ mailsy g
random@email.com
```

**获取电子邮件**

**请注意：**

点击 Enter 在默认浏览器中打开电子邮件。

```console
foo@bar:~$ mailsy m
? Select an email (Use arrow keys)
❯ 1. Hello, World! - from m.asghar99@outlook.com
  2. Mailsy - from m.asghar99@outlook.com

```

**删除账户**

如果您想删除电子邮件并获取新邮件，请使用：

```console
foo@bar:~$ mailsy d
Account deleted
```

**账户详情**

```console
foo@bar:~$ mailsy me

 Email: random@random.com
 createdAt: 13/03/2022, 21:32:09

```
