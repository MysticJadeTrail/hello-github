# hello-github

我的第一个 GitHub 仓库，用于验证 SSH 连接与 Git 基本工作流。

## 环境信息

- 连接方式：SSH（端口 22），备用通道 443
- 密钥类型：ed25519
- 默认分支：main

## 常用命令速查

```bash
git status                  # 查看工作区状态
git add .                   # 暂存所有改动
git add 文件名               # 只暂存指定文件
git commit -m "说明"         # 提交到本地仓库
git push                    # 推送到 GitHub
git pull                    # 拉取远端更新
git log --oneline -10       # 查看最近 10 条提交
git remote -v               # 查看远程地址
```

## 工作流口诀

改文件 → `git add` → `git commit` → `git push`

三步不能跳过：不 `add` 的改动不会被提交，不 `commit` 的改动无法推送。

## 提交信息怎么写

好的提交信息说明"做了什么、为什么"：

- 好：`修复登录页在 Safari 下按钮错位`
- 差：`update`、`修改`、`fix bug`

## 隐私说明

本仓库提交邮箱使用 GitHub 提供的 noreply 地址，
不会暴露真实邮箱。

---

创建于 2026-11-25
