# MIT 6.824 (Spring 2020)

MIT 6.824 分布式系统课程的资料与实践，来源：[Spring 2020](http://nil.csail.mit.edu/6.824/2020/)。

## 目录

```
docs/
  lectures/          讲义
  papers/            论文 PDF + FAQ
  lab-instructions/  Lab 说明
  exams/             历年试卷
  code-samples/      课堂 Go 示例
  website/           课程页面（schedule 等）
  INDEX.txt          讲座、论文、Lab 对照表

lab-code/            官方 Lab 骨架代码（未实现）
```

## Lab

四个 Lab：MapReduce → Raft → KV Raft → Sharded KV。

代码在 `lab-code/`，说明在 `docs/lab-instructions/`。使用 GOPATH 模式：

```bash
cd lab-code
export GO111MODULE=off
export GOPATH=$HOME/go:$(pwd)
export PATH=$PATH:$(pwd)/bin

# Lab 1 测试
cd src/main && sh test-mr.sh
```

Lab 骨架来自 `git://g.csail.mit.edu/6.824-golabs-2020`。
