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

