## 第一次Git实验总结 
1. git add 的作用是：将工作区中修改的文件加入暂存区，标记哪些变更准备提交，并不会生成本地版本。
2. git commit 的作用是：把暂存区的改动保存成本地版本快照，生成commit记录，改动仅保存在本地电脑。
3. git restore notes.md 的作用是：丢弃工作区没有暂存的修改，把notes.md恢复到最近一次commit保存的状态。
4. commit 与 push 的区别是：commit仅在**本地仓库**生成版本；push将本地已经commit的版本上传推送到GitHub远程仓库。