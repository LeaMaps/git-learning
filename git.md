# GIT

## git配置

> git config <选项>

git配置文件主要保存在三个地方：

- /etc/gitconfig：系统配置，对应选项`--system`
- ~/.gitconfig或~/.config/git/config：用户配置，对应选项`--global`
- .git/config：用户配置，对应选项`--local`

> 配置查看

```shell
# 按搜索顺序显示配置信息
git config --list
# 显示配置信息以及其保存的文件路径
git config --list --show-origin
# 显示最后一次修改的该配置的值（默认是仓库的配置）
git config --show-origin user.name
```

## git获取帮助

```shell
# 按帮助工具格式
git help <命令>
# 按选项格式
git <命令> --help
git <命令> -h
# man工具
man git config
```



