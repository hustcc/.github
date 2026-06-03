<p align="center">
  <a href="https://github.com/lint-md">
    <img width="128" src="https://avatars.githubusercontent.com/u/59811714">
  </a>
</p>

<p align="center">让中文 Markdown 写作更规范、更一致。</p>

<p align="center">Lint your Chinese Markdown for cleaner, more consistent writing.</p>

<img src="https://avatars.githubusercontent.com/u/59811714" width="16" /> lint-md ![stars](https://img.shields.io/github/stars/lint-md?style=social) 是专注中文 Markdown 规范化的开源组织。我们围绕 AST 构建可扩展的规则体系与自动修复能力，提供从底层解析到上层工程化接入的一站式工具链，帮助团队在文档、博客与知识库场景中持续输出统一、可维护的内容质量。

### 项目体系

#### 1.底层 AST 插件机制

- [`lint-md/ast-plugin`](https://github.com/lint-md/ast-plugin)：轻量 AST 遍历与插件机制，便于规则扩展。
- [`lint-md/parser`](https://github.com/lint-md/parser)：基于 remark 生态的 Markdown 解析器。

#### 2. lint-md 核心实现

- [`lint-md/lint-md`](https://github.com/lint-md/lint-md)：规则引擎与 fix 能力核心实现。

#### 3. 上层使用方式封装

- [`lint-md/cli`](https://github.com/lint-md/cli)：命令行工具。
- [`lint-md/prettier-plugin`](https://github.com/lint-md/prettier-plugin)：Prettier 插件集成。
- [`lint-md/eslint-plugin`](https://github.com/lint-md/eslint-plugin)：ESLint 插件集成。
- [`lint-md/github-action`](https://github.com/lint-md/github-action)：GitHub Action 集成。
- [`lint-md/vscode-plugin`](https://github.com/lint-md/vscode-plugin)：VSCode 编辑器集成。

## 开源贡献

欢迎通过 [Issues](https://github.com/lint-md/lint-md/issues) 提建议、报问题，或通过 [Pull Requests](https://github.com/lint-md/lint-md/pulls) 直接参与共建。
