# just for test
sometimes , I am in ... `Iridescent`

## git learn!!!
it is so interesting!

## now ,it's note

刚刚学完，做个笔记

> 这让我想起了当初第一次接触github的时候，刚刚开始学习java，学的未免太痛苦了；<br/>
> 也忘记了我是怎么学习的，看着那么一大摊子的英文，各种`commit`,`york`,`branch`,真的太累了。<br/>
> 也许，就应该先学习一下git，然后再去学**github**，这样才不会那么累吧，太痛苦了，直接让我知难而退了，唉。

[学习地址](http://stormzhang.com/github/2016/05/30/learn-github-from-zero1/)

### 简单教程来了

安装完成后，就找个地方测试：

1. 找个文件目录，里面建立一个文件，例如 `git.md`;
2. 进入`git`控制台，这个跟windows的控制台一样的，使用`cd`命令进去就好，进入当前文件目录地址；
3. 先要初始化，使用`git init`，就可以开始初始化工作了；
4. 给`git.md`写入一点东西，然后就可以尝试提交至仓库了；
5. 使用`git add [file_name]`命令，这个是指，把当前文件，暂时提交上去，再使用`git commit -m "something say"`来真正提交上去，这是为了避免出错的一种机制吧，还有`git status`可以查看当前状态；
6. 使用`git log`，查看提交日志；
7. 使用`git tag v1.0`，可以建立一个版本：`v1.0`，`git tag`查看全部日志，`git checkout v1.0`进去这个版本；
8. 分支，`git branch`，查看全部分支，`git branch a`：建立一个 a 的分支，`git checkout a`，选择这个分支，`git merge a `合并 a 分支， 使用`git branch -d a `:删除 `a`分支，若是`-D`,则会强制全部删除。

**以上**，还挺简单的！
