## 提交信息格式规范

``` 格式
<header>
<body>
<footer>
```

### header
```
<type>:<subject>
```
#####type
* feat:新功能
* fix:修补bug
* doc:文档
* style:格式(不影响代码运行的变动)
* rafactor:重构(即不是新值功能，也不是修改bug的代买变动)
* test:增加测试
* chore:构建过程或辅助工具的变动
#####subject
subject 是commit目的的简短描述
* 以动词开头，使用第一人称现在时，eg. change /不是(✘changed/changes)
* 第一个字母小写
* 结尾不加句号

###body
对本次commit的详细描述，可以分成多行
```
More detailed explanatory text, if necessary.  Wrap it to 
about 72 characters or so. 

Further paragraphs come after blank lines.

- Bullet points are okay, too
- Use a hanging indent
```
###footer
用于试用几种情况
* 关联Issue
* 关闭Issue

####关联Issue
```
Issue #1, #2, #3
```
####关闭Issue
```
Close #1, #2, #3
```

###例子
```
feat: 添加了分享功能

给每篇博文添加了分享功能

- 添加分享到微博功能
- 添加分享到微信功能
- 添加分享到朋友圈功能

Issue #1, #2
Close #1
```