---
title: AI 应用开发
category: AI应用开发
tags:
  - AI应用开发
  - 学习索引
---

# AI 应用开发

这里保存 AI 应用开发笔记的主稿。日常学习、补充和修订先在知识库进行，需要公开分享时，再把选定文章同步到博客。

## 基础概念

1. [大语言模型基础](<基础/1. 大语言模型基础.md>)：LLM、Token、上下文窗口、采样参数、Prompt、结构化输出和工具调用。
2. [AI Agent 基础](<基础/2. AI Agent 基础.md>)：Agent Loop、ReAct、规划、工作流、上下文、记忆、MCP、Skills 与工程化。

## Transformer

- [Attention Is All You Need：Transformer 开山之作](<Transformer/1. Attention Is All You Need.md>)：原始论文、注意力机制与 Transformer 架构。

## 主稿与博客的对应关系

知识库根目录：`/Users/camellia/Books/CAMELLIAKnowledgeBase`

博客项目：`/Users/camellia/workspace/eleven52ac/starlightBlog`

以下知识库路径相对于本目录，博客路径相对于博客项目根目录：

| 知识库主稿 | 博客发布副本 |
|------------|--------------|
| `基础/1. 大语言模型基础.md` | `src/content/docs/Agent/基础/1. 什么是 LLM.md` |
| `基础/2. AI Agent 基础.md` | `src/content/docs/Agent/基础/2. AI Agent 基础.md` |
| `Transformer/1. Attention Is All You Need.md` | `src/content/docs/Agent/Transformer/1. Attention Is All You Need.md` |

这三篇文章已经在博客发布。2026-11-01 将当时的博客版本归档到知识库，自此以这里的笔记作为后续维护的主稿，已发布副本继续保留。

## 按需同步发布

1. 平时只更新知识库主稿，不自动改动或推送博客。
2. 用户明确要求同步或发布时，先查看选定文章对应的博客文件是否有独立改动；如有差异，先将需要保留的修改合并到知识库主稿。
3. 从知识库单向同步所选文章到上表对应的博客路径，不批量同步整个知识库。保留必要的文章元数据和现有博客文件名，避免改变已发布链接。
4. 将本地笔记链接转换为博客页面链接。例如，Agent 文章中指向 `1. 大语言模型基础.md` 的链接，发布时应转换为 `/agent/基础/1-什么是-llm/`；转换只作用于发布副本。
5. 按需更新博客导航，运行 `npm run build` 并核对文章页面和内链。用户要求发布时，检查完成后直接提交并推送博客，无需再次询问。

目前没有设置自动同步、自动发布脚本或定时任务。
