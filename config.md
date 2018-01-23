# Global config

## 增加配置
这里会修改用户目录`(~)`下的`.gitconfig`文件:
```git
$git config --global user.name "yourname"
$git config --global user.email "youremail@host.com"
```

为`git`添加一些别名:
```git
$git config --global alias.st status
$git config --global alias.ci commit
$git config --global alias.co checkout
$git config --global alias.br branch
```

使`git` 在输出时候开启颜色显示:
```git
$git config --global color.ui true
```

## 删除配置

```git
$git config unset --global user.name
$git config unset --global user.email
```
