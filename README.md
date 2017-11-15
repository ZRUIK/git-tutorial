# Git Tutorial
Git 的学习和配置教程

## 1. 深入学习 Git 的参考地址
[官网教程](https://git-scm.com/doc)

[Git教程 - 廖雪峰](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

## 2. Git commit 规范

参考于 [Angular 规范](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)

```
type: subject

body

footer
```

### 对格式的说明如下
#### type
代表某次提交的类型，比如是修复一个 bug 还是增加一个新的 feature。所有的 type 类型如下：
- feat: 新增 feature
- fix: 修复 bug
- docs: 仅仅修改了文档，比如 README，CHANGELOG，CONTRIBUTE 等等
- style: 仅仅修改了空格、格式缩进、都好等等，不改变代码逻辑
- refactor: 代码重构，没有加新功能或者修复 bug
- perf: 优化相关，比如提升性能、体验
- test: 测试用例，包括单元测试、集成测试等
- chore: 改变构建流程、或者增加依赖库、工具等
- revert: 回滚到上一个版本

#### subject
标题行：50 个字符以内，描述主要变更内容

#### body（可选）
主体内容：更详细的说明文本，建议 72 个字符以内。 需要描述的信息包括:

- 为什么这个变更是必须的? 它可能是用来修复一个 bug，增加一个 feature，提升性能、可靠性、稳定性等等
- 是否存在副作用、风险? 

#### footer（可选）
尾部：如果需要的话，可以添加一个链接到 issue 地址或者其它文档，或者关闭某个 issue。

## 3. 在 Windows 上的 Git

### 3.1. Visual Studio 中内置的 Git 工具 

#### 3.1.1. Visual Studio 配置 Git 的参考地址
[如何在 Visual Studio 2013 上使用 Github](http://www.oschina.net/translate/setting-up-github-to-work-with-visual-studio-2013-step-by-step)

[如何在 Visual Studio 中配置 git](http://jingyan.baidu.com/article/3a2f7c2e05273926afd6118d.html)

#### 3.1.2. Visual Studio 使用 Git 的参考地址
[VS2015 Git 源码管理工具简单入门](http://www.cnblogs.com/newP/p/5732431.html)

[VS2015 Git 插件使用教程](http://blog.csdn.net/huutu/article/details/51099143)

### 3.2. 在 Windows 上搭建 Git Server(Gitblit)
[在 Windows 上搭建 Git Server](http://www.cnblogs.com/sumuncle/p/6362697.html)

[Windows 平台下 Git 服务器搭建](http://blog.csdn.net/a117653909/article/details/51182188)
