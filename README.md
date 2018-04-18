# 仿淘宝首页

> 开始时间： 2018-04-15

```
2018-04-15,提交了全部的图片素材，还提交了顶部区域以及logo和搜素区域的代码
2018-04-16,提交了导航区域的代码
2018-04-17,熟悉git命令
2018-04-18,git命令的操作
2018-04-18,优化了之前写的id全部更换为class
```

# 这里写一些关于我学习git命令的一些资料

## 配置Git的整理
```
git config --global user.name "这里写你的用户名"		配置你的用户名
git config --global user.email "这里写你的邮箱"			配置你的邮箱
ssh -T git@github.com 									测试SSH key是否设置成功
ssh-keygen -t rsa -C "你的邮箱" 						生成密匙
git config user.name 									查看你配置的用户名
git config 指定的属性名									查看你相对应的属性的值，然后返回给你

```

## 创建和扩隆仓库
```
git init        										初始化你的仓库
git clone 远程仓库的地址    							扩隆远程地址的代码到本地仓库
git config --list 										获取git的配置信息

```

## 提交跟历史
```
git log 												查看提交的历史
git log -p 指定的文件名									查看指定文件的提交历史
git blame 指定的文件名									以列表的方式查看指定文件的提交历史

git add 文件名  										提交指定文件到暂存区
git add .       										提交全部修改的文件到暂存区
git commit -m "这里写你这次提交的描述"					提交所有更新过的文件
```

## 分支和标签
```
git branch 												显示所有的分支
git checkout 分支名或者标签名							切换到指定的分支或标签
git branch 新的分支名 									基于当前的分支创建新的分支
git branch -d 分支名 									删除本地的分支
git tag 												列出本地所有标签
git push --tags 										发布所有标签
```

## 更新跟发布
```
git remote -v 											查看远程版本库的信息
git remote show 指定的文件地址							查看指定远程版本库的信息
git pull   												更新远程代码到本地的仓库
git pull 远程地址 分支名 								下载远程所有改动到本地，自动合并到当前（下载远程代码及快速合并）
git push 远程地址 分支名 								将本地版本发布到远程端（上传本地代码到远程端）
git push -u origin master   							本地提交代码到远程仓库
```

## 撤销
```

```

## 文件操作
```
git mv 旧文件名	新文件名								文件改名字
git rm 文件名 											删除指定的文件名
git rm --cached 文件名 									停止跟踪文件但不删除
```

## 远程仓库的使用
```
git remote add 别名 远程地址 							添加一个远程地址并且添加别名，好操作
git fetch 别名											
```
