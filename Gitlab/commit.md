基于 Commitizen 形式的提交信息：

一种通用的提交信息格式，通过命令行工具可以轻易的提交固定格式的信息。
通常会是这样的

![](https://raw.githubusercontent.com/commitizen/cz-cli/master/meta/screenshots/add-commit.png)

- 好处？

- 如何配置？
官方教程，使用 `git-cz`
然后在你的 `package.json` 上写出对应的脚本，例如 `Angular` 里面的：
https://github.com/angular/angular.js/blob/master/package.json#L17

谁在用？


### Angular commit guideline

[Angular Git Commit Guidelines](https://github.com/angular/angular.js/blob/master/CONTRIBUTING.md#commit)

- 易于理解
- 生成更新日志

#### 相关格式
```
<type>(<scope>): <subject>
<BLANK LINE>
<body>
<BLANK LINE>
<footer>
```

#### type - 指定类型

- feat: A new feature
- fix: A bug fix
- docs: Documentation only changes
- style: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- refactor: A code change that neither fixes a bug nor adds a feature
- perf: A code change that improves performance
- test: Adding missing or correcting existing tests
- chore: Changes to the build process or auxiliary tools and libraries such as documentation generation

#### scope - 影响区域

修改的代码所影响的区域

#### subject - 