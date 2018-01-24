# Git Operations

## 初始化版本库

初始化一个版本库, 在需要建立版本库的根目录使用下面的命令:
```git
$cd /path/to/your/workspace
$git init
>Initialized empty Git repository in /path/to/your/workspace/.git/
```

你也可以采用如下方式来建立版本库:

```git
$git init /path/to/your/workspace 
```

## 查看版本库状态

```git
$git status
```

## 添加文件

假如我们创建了一个文件名为`helloGit.txt`,
我们可以采用如下方法将其添加到版本库中:
```git
$git add helloGit.txt
```

## 提交

```git
$git commit -m "提交说明"
```

## 查看提交日志

`--stat` 参数的意思是我们可以看到每次提交的文件变更.
```git
$git log [--pretty=fuller[--stat]]
```

## 查看文件内容变更

`git diff`
如果不带任何参数和选项,则表示显示工作区的最新改动,即工作区与暂存区中相比的差异.
如果带了参数`--cached` 或者是`--staged`,则看到的是暂存区和版本库中文件的差异.
```git
$git diff
```

## 分支管理

```git
$git branch
```

## 重置

```git
$git reset --hard 'ID'
```
