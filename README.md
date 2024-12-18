# ZJUCSA-crypto-basic
如果你想在本地部署文档，可以使用以下指令
```console
$ pip3 install mkdocs-material mkdocs-heti-plugin
$ git clone https://github.com/fkrcarry/ZJUCSA-crypto-basic.git
$ cd ZJUCSA-crypto-basic
$ mkdocs serve
```
本仓库结构如下
```
├── README.md 
├── docs/                       # 实验文档
├── mkdocs.yml 
└── task.zip/                   # 题目汇总
    ├── attachment1
    └── attachment2             # 不同题目的附件
        ├── task.txt            # 题目
        └── resource.zip        # 每个附件都会有一个resource.zip，其解压密码是解出来的flag
            └── taskchuti.c     # 出题的源码
```
