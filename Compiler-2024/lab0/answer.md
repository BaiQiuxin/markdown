# PB22111688 向哲煜

## 实验二

### 实验任务

#### 1

已完成

#### 2  

创建分支可以通过

```git
git branch <name>
git checkout -b <name>  //创建并切换
git switch -c <name>  // 创建并切换
```

切换分支可通过

```git
git switch <name>
git checkout <name>
```

删除分支可通过

```git
git branch -d <name>
```

当该分支的修改已经合并到其他分支时或者主分支，分支的修改不会丢失时，可以安全地删除该分支。

撤销保存在暂存区的修改

```git
git reset HEAD <file>
```

撤销最近一次提交的某一个文件

```git
git checkout -- test.txt
```

git pull的会将本地的代码更新至远程仓库里面最新的代码版本

git fetch更新代码，本地相当于存储了两个代码的版本，我们还要通过merge去合并这两个不同的代码版本.

#### 3

已完成

## 实验三

1. 使用了已经删除的函数Student()
2. 未向函数check()中传入参数
3. 调用了已经释放掉的地址
