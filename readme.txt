git is a version control system.
git is free software.

Git is a distributed version control system.
Git is free sotfware.

git has a mutable index called stage.

MY stupid boss still prefers SVN.

小结：两点内容
    1.初始化一个 Git 仓库 使用 git init 命令
    2.添加文件到Git仓库，分成两部：
        使用命令 git add <file>
        使用命令 git commit -m <message> 
版本回退 小结：
    1. git status 命令可以让我们时刻掌握仓库当前的状态
    2.HEAD指向的是当前版本，因此，Git允许我们在版本的历
    史之间穿梭，使用命令 git reset --hard commit_id
    3.穿梭前，用git log可以查看提交历史，以便确定回退到
    哪个版本。
    4.要重返未来，用git reflog 查看命令历史，以便确定回
    到那个版本
撤销修改 小结：
    场景 1 ： 当你改乱了工作区某个文件的内容，想直接丢掉
    工作区的修改是，用命令 git checkout -- file
    场景 2 ： 当你不但改乱了某个工作区的内容，还添加到了
    暂存区时，想丢弃修改，分成两步，第一步用命令
    git reset HEAD <file> 就删除了暂存区中内容，回到场
    景 1，按场景1 继续操作即可。
    场景 3 ： 已经提交了不合适的修改到文本库中，想要撤回
    本次提交，参考版本回退一节（前提是没有推送到远程库）