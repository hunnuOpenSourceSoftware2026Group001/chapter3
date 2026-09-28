# 我的 Git 学习笔记
## 本地Git实验过程
1. 创建 `git‑course‑simple` 文件夹，在其中建立 `local‑practice` 练习目录。
2. 在练习目录执行 `git init -b main`，初始化本地Git仓库。
3. 配置Git用户名和邮箱，与自己的GitHub账号信息保持一致。
4. 创建笔记文件 `notes.md` 和学习计划文件 `plan.md`。
5. 使用 `git add` 将文件加入暂存区，让Git跟踪这些文件。
6. 使用 `git commit` 将暂存区的改动保存成本地版本快照。
7. 修改notes.md写入测试文本，再使用`git restore`撤销未提交的修改，恢复文件。
8. 删除plan.md文件，再使用`git restore`恢复被删除的文件。

## 第一次Git实验总结
1. git add 的作用是：把工作区的变更添加到暂存区。
2. git commit 的作用是：将暂存区内容保存为本地版本快照。
3. git restore notes.md 的作用是：撤销工作区未暂存的修改，恢复文件到最近一次提交状态。
4. commit与push的区别是：commit保存到本地仓库；push把本地提交上传到远程仓库。