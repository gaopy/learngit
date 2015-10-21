---
title: github for windows 学习笔记
tags: github,笔记
grammar_cjkRuby: true
---

## 配置github
1. github 安装 [官方下载地址][1]
2. 接入github 
>git config --global user.name "Yourname"
git config --global user.email "example@email.com"
`cd E:\\mrgao\onedrive # connect directory`
`mkdir newfile  # make directory`
`pwd # put out workdirectory`
2. 操作版本库
    + 新建版本库        `git init`
    + 添加文件到版本库  `git add filename.xxx`
    + 提交文件到版本库  `git commit -m "修改说明"`
    + 获取当前版本状态  `git status`
    + 获取修改信息      `git diff`
    + 获取提交日志      `git log    \ git log --pretty = oneline`
    + 退回之前版本      `git reset --hard HEAD^ # HEAD~5 `退回五次前的版本`
    + 获取命令历史      `git relog`
    + 进入某个版本      `git reset --hard "commit_id" #commit_id 可通过git relog 获取`

  [1]: https://git-for-windows.github.io/