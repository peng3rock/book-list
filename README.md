
# 如何下载书

+ 1. 复制对应文件夹链接到 [DownGit](https://minhaskamal.github.io/DownGit/#/home)下载
+ 2. 解压后 进入加压文件夹使用 cat 命令拼接，例如:

```
cat subdate* > book.pdf
```

# Github上传大文件方法
使用分割命令 split, 例如
```
split -b 10M data subdata-
```
