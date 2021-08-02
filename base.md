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

<!-- 版本回退 -->
用HEAD表示当前版本
上一个版本就是HEAD^，上上一个版本就是HEAD^^，往上100个版本写成HEAD~100
git reset --hard 版本号  可以快速回退到想要的版本

git reflog 所有git 仓库 操作记录