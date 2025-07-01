# git_practices
Git 基本使用指南

## 1. Git 配置

首先需要配置你的身份信息：

```bash
git config --global user.name "你的名字"
git config --global user.email "你的邮箱"
```
git branch -a 
查看分支情况

git checkout -b 分支名
切换到指定分支

git merge 分支名
合并分支

git tag 步骤
1. 先拉去 `git checkout 1.0.2-RELEASE`
2. 修改内容标签
3. 打tag `git tag 1.0.3-RELEASE`
4. 推动tag `git push origin 1.0.3-RELEASE`

删除tag 本地/云端
git tag -d 1.0.3-RELEASE
git push origin -d 1.0.3-RELEASE


---

1. 拉取tag 
2. 修改内容
3. merge develop
4. tag 1.0+
5. push

---

1. 拉取tag
2. checkout -b feature/1.0.5
3. 修改内容
4. add .  commit
5. push orin feature/1.0.5
6. git tag 1.0.5
7. git push origin 1.0.5



## conflix


i will push this


push conflix
i will push two times

## confict2
i will sovle it

time to solve


## conflict 3

git pull --rebase
git rebase --continue
git rebase --continue
git checkout main
git push





solve it!!!


## conflict 4

git push --rebase

git rebase --continue
git add .
git rebase --continue
git checkout main
git push



solve


----

## no rebase


1. git stash
2. git pull
