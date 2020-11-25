# 有两种方式操作

## 一.命令行

* 添加需要远程的仓库地址

```git
    git remote add all https://github.com/1206589598Colin/blog.git
    git remote add all https://gitee.com/ColinWWL/blog.git
```

* 提交时输入代码

```git
    git push all --all
```

## 二、直接配置.git/config文件

```git
    [remote "all"]
        url = https://github.com/abel533/Mapper.git
        url = https://git.oschina.net/free/Mapper.git
```
