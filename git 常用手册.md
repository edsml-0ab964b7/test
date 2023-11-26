```bash
查看文件更改 git diff
git add .  
		git restore --staged filename  取消提交，恢复存档
git commit -a -m ""
		git commit -amend -m "new commit"  重命名提交短语
git push

1. 查看提交记录
$ git log
$ git log --oneline --all --graph

2. 分支
$ 创建分支 git branch feature-1
$ 查看分支 git branch
$ 切换分支 git switch feature-1
				  git checkout feature-1
				  
3. 合并
$ 切换分支 git checkout main  要合并到的分支
$ 合并 git merge [branch]

4. 忽略提交 .gitignore

5. 回溯历史
$ git restore filename  取消提交，恢复存档
$ git reset --hard 2b4jfe32		用id回溯历史提交
$ 查看历史操作记录 git refloglog

```

