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
    3. git status 命令可以让我们时刻掌握仓库当前的状态
    4.HEAD指向的是当前版本，因此，Git允许我们在版本的历
    史之间穿梭，使用命令 git reset --hard commit_id
    5.穿梭前，用git log可以查看提交历史，以便确定回退到
    哪个版本。
    6.要重返未来，用git reflog 查看命令历史，以便确定回
    到那个版本