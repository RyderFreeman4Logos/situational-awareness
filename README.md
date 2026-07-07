# 情境意识：AGI 与超级智能（中文译文）

本仓库收录 [situational-awareness.ai](https://situational-awareness.ai) 的中文译文，由 **GPT-5.5-Pro** 翻译。

## 章节概览

本仓库包含 9 篇中文译文（编号 0–8），涵盖 AGI 竞赛、超级智能前景、对齐难题、美国 AI 实验室安全等主题。

- 请通过 [GitHub Pages](https://ryderfreeman4logos.github.io/situational-awareness) 或本地 `mdbook serve` 浏览完整内容。

## 在线阅读

通过 [mdBook](https://rust-lang.github.io/mdBook/) 编译的 GitHub Pages 页面：

> **https://ryderfreeman4logos.github.io/situational-awareness**

## 本地编译

```bash
# 安装 mdBook
cargo install mdbook

# 编译
mdbook build

# 预览
mdbook serve
```

## 构建流程

仓库使用 GitHub Actions 自动编译并部署到 GitHub Pages：

1. 推送至 `main` 分支 → 触发 CI
2. `mdbook build` 生成静态站点
3. `gh-pages` 部署动作将 `./book` 目录发布到 GitHub Pages

## 翻译说明

- **原文来源**：[situational-awareness.ai](https://situational-awareness.ai)
- **翻译引擎**：GPT-5.5-Pro
- **翻译格式**：Markdown（`.md`）
