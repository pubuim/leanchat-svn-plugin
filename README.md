# LeanChat-SVN-Plugin

零信 SVN 服务通知

目前支持的提醒如下

- Commit

欢迎 fork/pr 

## 如何使用

- 请现在零信上创建 SVN 服务然后，复制 hooks 地址，替换 `post-commit` 脚本中的第二行的 `HOOKS` 值

- 复制脚本到 SVN 对应仓库的 hooks 目录,并确保有执行权限

- 尝试提交一个 Commit 并且 Push，即可收到推送。Enjoy :)


