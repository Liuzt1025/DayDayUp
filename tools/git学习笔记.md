# GIt学习笔记

#### git免密码的配置方法

在git bash中输入以下命令:

```
git config --global credential.helper store
```

在用户目录下面创建.git-credential

使用vim写入:

```
https://ID:123456@github.com
```



![image-20210511215023014](git%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0.assets/image-20210511215023014.png)