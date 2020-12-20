# 贡献导引

请严格按照以下步骤操作，如有任何问题，请提出 issue

* 在 GitHub 上点击 `fork` 将本仓库 fork 到自己的仓库，如 `yourname/nginx-book`，然后 `clone` 到本地。

```bash
$ git clone git@github.com:yourname/nginx-book.git
$ cd nginx-book
# 将项目与上游关联
$ git remote add source git@github.com:shunyue1320/nginx-book.git
```

* 增加内容或者修复错误后提交，并推送到自己的仓库。

```bash
$ git add .
$ git commit -am "Fix issue #1: change helo to hello"
$ git push origin master
```

* 在 GitHub 上提交 `pull request`。

* 请定期更新自己仓库内容。

```bash
$ git fetch source
$ git rebase source/master
$ git push -f origin master
```

# 排版规范

本项目排版遵循 [中文排版指南](https://github.com/mzlogin/chinese-copywriting-guidelines) 规范。
