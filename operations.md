# Git Operations

## 初始化版本库

初始化一个版本库, 在需要建立版本库的根目录使用下面的命令:\
```git
$cd /path/to/your/workspace
$git init
>Initialized empty Git repository in /path/to/your/workspace/.git/
```

你也可以采用如下方式来建立版本库:\

```git
$git init /path/to/your/workspace 
```

## 查看版本库状态

```git
$git status
```

## 添加文件

假如我们创建了一个文件名为`helloGit.txt`,
我们可以采用如下方法将其添加到版本库中:\
```git
$git add helloGit.txt
```

## 提交

```git
$git commit -m "提交说明"
```

## 查看提交日志

```git
$git log --pretty=fuller
```
