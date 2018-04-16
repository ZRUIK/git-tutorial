# Git Tutorial

Git 的学习教程。

## 1. 深入学习 Git

[官网教程](https://git-scm.com/doc)

[Git 教程 - 廖雪峰](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

## 2. Git Commit Guidelines

参考 [Angular 规范](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)，格式说明如下：

```Text
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>

```

每个 commit 包括三个部分：header、body（可省略） 和 footer（可省略），之间通过一个空行相隔。

为了可读性，每行内容不应该超过 100 个字符。

### 2.1 header

header 由 type、scope 和 subject 组成。

```Text
<type>(<scope>): <subject>

```

#### 2.1.1 type

代表某次提交的类型，比如是修复一个 bug 还是增加一个新的 feature。所有的 type 类型如下：

- feat: 新增 feature
- fix: 修复 bug
- docs: 文档，比如修改了 README
- style: 格式，比如添加空格，不改变代码逻辑
- refactor: 代码重构，既没有添加新功能也没有修复 bug
- perf: 优化代码，比如提升性能
- test: 测试，添加缺失的测试，或纠正现有的测试
- chore: 改变构建流程、或者增加依赖库、工具等
- revert: 回滚到上一个版本

#### 2.1.2 scope

指明本次提交的改动范围。范围的划分需要根据项目的具体情况而定。当改动影响到一个以上的范围时可以使用 `*` 符号。

#### 2.1.3 subject

简短地描述本次提交的主要变更内容。英文格式要求如下：

- 使用一般现在时；
- 首字母不用大写；
- 末尾不用添加 `.` 符号。

### 2.2 body（可省略）

详细地描述本次提交的主要变更内容。英文格式跟 subject 一样，描述可以分成多行。

### 2.3 footer（可省略）

如果需要的话，可以添加一个链接到 issue 的地址：

```Text
issue #1

```

或者关闭某个 issue：

```Text
close #1

```

关于在 commit 关闭 issue 的详细方法请阅读 [《Closing issues using keywords》](https://help.github.com/articles/closing-issues-using-keywords/)。
