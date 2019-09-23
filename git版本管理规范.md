# 版本管理规范

------------

## 1、有模板的项目，要以统一的模板创建项目

## 2、git commit 规范

git commit 提交样式标准
```
<类型>: <标题>
<空一行>
<内容>
<空一行>
<结尾>
```

**<类型>**
用于说明 commit 的类别，只允许使用下面7个标识。
- feat：新功能（feature）
- fix：修补bug
- docs：文档（documentation）
- style： 格式（不影响代码运行的变动）
- refactor：重构（即不是新增功能，也不是修改bug的代码变动）
- test：增加测试
- chore：构建过程或辅助工具的变动
 
**<题目>**
commit 目的的简短描述，不超过50个字符
 
**<内容>**
对本次 commit 的详细描述，可以分成多行，可详细说明代码变动的动机
 
**<结尾>**
如果当前 commit 针对某个issue，那么可以在 Footer 部分关闭这个 issue：
Closes #234