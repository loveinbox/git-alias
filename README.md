## 一些个人常用的git命令

提升效率

```
// 直接推至远端，适合很小的修改。
// 优点：无需写commit message
alias cf="git add . && git commit --amend --no-edit && ggpush -f"

// 开发RN时快速安装app
alias rrn='xcrun simctl install booted /Users/bingzhuren/Documents/app/discover.app'

// 快速增加commit message
alias gmm='git commit -m'

// sublime的快捷打开方式
alias sl=\''/Applications/Sublime Text.app/Contents/SharedSupport/bin/subl'\'
```