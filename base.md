1234123
24353543

配置
git config --global user.name "xiaoyu"
git config --global user.email "xiaoyu@xx.com"

操作
git init

11111111111111111111111111111111

添加到仓库
git add base.md

git commit -m '本次提交描述'

22222222222222


添加到仓库完成  有一个版本

查看所有版本
git log

33333333333333

查看仓库状态
git status
4444444444444444


撤销
git restore

撤销工作区更改
git restore file

从暂存区撤销更改
git restore --staged file

<!-- 生成sshkey，只生成一次就可，不需要反复生成 -->
ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

<!-- 版本回退 -->
用HEAD表示当前版本
上一个版本就是HEAD^，上上一个版本就是HEAD^^，往上100个版本写成HEAD~100
git reset --hard 版本号  可以快速回退到想要的版本

git reflog 所有git 仓库 操作记录

------------------------------------------
GitHub 的3句代码

关联远程仓库
git remote add origin git@github.com:Xiaoxiaoyu2021/git-test.git

git branch -M main


推送到远程仓库
git push -u origin main
