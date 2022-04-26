### 1. 复制.myalias 和 .myprofile
```

将 .myalias 和 .myprofile (.myprofile暂且不拷贝，有些问题还没有完善好) 两个文件复制到用户的家目录下

```


### 2. 修改用户家目录下的启动加载配置文件(每种系统环境可能略微不同)
```

2.1 Msys2或Mac系统
    vim ~/.bash_profile
    . ~/.myalias
    . ~/.myprofile
    source ~/.bash_profile

2.2 Linux系统
    vim .profile
    . ~/.myalias
    . ~/.myprofile
    source ~/.profile

```
