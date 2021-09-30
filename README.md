## 一些个人常用的git命令

提升效率

```
# 直接推至远端，适合很小的修改。
# 优点：无需写commit message
alias cf="git add . && git commit --amend --no-edit && ggpush -f"

# 删除已merge的分支
alias gbdd="git pull -p;git branch -d \$(git branch --merged | egrep -v 'master|develop|^\*' | xargs)"

# 安装加启动命令
alias dd="yarn && yarn serve"

# autojump的快捷方式
[[ -s `brew --prefix`/etc/autojump.sh ]] && . `brew --prefix`/etc/autojump.sh
```
