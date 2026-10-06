## 第一次 Git 实验总结
1. `git add` 的作用是：
把工作区的文件修改，添加到暂存区，标记待提交，修改还没有存入版本库。

2. `git commit` 的作用是：
把暂存区改动生成版本快照，保存到本地Git仓库，生成commit记录。

3. `git restore notes.md` 的作用是：
用最近一次提交的notes.md覆盖工作区，撤销还没add的本地修改。

4. `commit` 与 `push` 的区别：
commit：仅保存版本到**本地电脑仓库**，不上传远程。
push：把本地已经commit的版本，上传推送到GitHub远程仓库。
