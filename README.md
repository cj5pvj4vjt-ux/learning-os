# Learning OS · 个人学习工作台

> 把数学、英语、科学、编程、知识管理和 AI 助手收进同一个浏览器工作区。
>
> **在线使用：<https://app.f7vr9hfw.icu/>**

## 这是什么

一个给自己用的个人学习工作台。所有练习数据默认留在本机浏览器，服务器只保存访问统计与 AI 助手的每日额度。

| 工作区 | 内容 |
| --- | --- |
| 数学 | SymPy 符号计算（8 类运算）、LaTeX 公式实时排版、GeoGebra 作图、浏览器内 Python 笔记本 |
| 英语 | 托福口语模考入口、Integrated Writing 与 Academic Discussion 计时写作、Anki 同步配置 |
| 科学 | 物理 / 天文 / 实验 / 数据分析的主题索引，收录 PhET、Tracker、Falstad |
| 编程 | Java、Python、TypeScript 草稿编辑器，模板 + 语法高亮 + 导出 |
| 知识 | 笔记、错题本、公式收藏、本机浏览记录 |
| AI 助手 | OpenAI 兼容对话，Markdown 与 LaTeX 渲染，按天限额 |

## 技术栈

Next.js 16（App Router / standalone）· React 19 · TypeScript 5.9 · Tailwind CSS 4 · Radix UI · zustand · MathJax 本地托管

部署在阿里云 ECS，Cloudflare Tunnel 出网，systemd 托管单实例 Node 进程。

## 链接

- 站点：<https://app.f7vr9hfw.icu/>
- GeoGebra 画板：<https://geo.f7vr9hfw.icu/>
- JupyterLite：<https://jupyter.f7vr9hfw.icu/>
- Anki 同步：<https://anki.f7vr9hfw.icu/>

---

源码未公开。这个仓库用于记录项目说明与入口。
