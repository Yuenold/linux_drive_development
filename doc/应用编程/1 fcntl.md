# fcntl

对文件描述符的一些操作函数

比例复制文件描述符

```
fd1 = open("./test_file", O_RDONLY);
fd2 = fcntl(fd1, F_DUPFD, 0);
这样操作fd2就是操作test_file文件
PS:0是指定了fd2从哪里开始
```



