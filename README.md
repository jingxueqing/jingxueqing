# 景雪晴 · JingXueQing

**工商管理专业** | 学号 2024102110351 | 郑州西亚斯学院

> 工商管理专业，自学 AI Agent 工程，习惯用「跑通 → 验证 → 复盘」的方式，把课程里的想法做成可交付、可复现的东西。

---

## 关于我

非计算机专业，但从 2026 年 9 月起持续用 AI Agent 做真实的交付物，而不是只写文档。
判断一件事做完没有，我的标准是：**能不能在别人的机器上复现**。

- 正在学：Python 工程化、Git 协作流程、Agent 技能（Skill）设计
- 工作方式：先读源码和测试，再动手；改完必跑回归
- 交付习惯：每个挑战都附 AI 使用日志 + 事后复盘（AAR），标明哪些是 AI 做的、哪些是我判断的

## 我关注的仓库

| 仓库 | 说明 |
|---|---|
| [sias-local-map-agent](https://github.com/jingxueqing/sias-local-map-agent) | 完全离线的本地大模型地图 Agent：一句自然语言 → 中英双语可交互腾讯地图 HTML，零 API 费用、数据不出本机，77 个离线测试全绿 |
| [my-challenges](https://github.com/jingxueqing/my-challenges) | 课程挑战（Elite20 / CogSeed）的资料、交付物与提交记录 |
| [neoskills](https://github.com/jingxueqing/neoskills) | fork 自 [neolaf2/neoskills](https://github.com/neolaf2/neoskills)，Agent 技能库，用于 C5A 仓库理解与贡献 |

## 最近的开源贡献

**PR [#4](https://github.com/neolaf2/neoskills/pull/4)** → `neolaf2/neoskills`：`docs: fix v0.2 paths in bundled skill/agents + add TROUBLESHOOTING.md`

- 2 个 commit，4 个文件，+200 / −27，纯文档改动
- 修掉 3 个「给 Agent 当指令执行」的文件里残留的 v0.2 路径（`registry.yaml` / `state.yaml` / `LTM/mappings/`）和 3 条已从 CLI 删除的命令
- 新增 `docs/TROUBLESHOOTING.md`，6 类故障每条都在 Python 3.13.12 / uv 0.12.5 / v0.4.2 上复现过
- 改动前后各跑一遍回归：`uv run pytest -q` → 172 passed，`ruff check` + `ruff format --check` 全绿

## 我用的工具

`Python 3.13` · `Git` · `uv` · `pytest` · `ruff` · AI Agent（文档处理、代码理解、自动化验证）

## 联系

- GitHub：[@jingxueqing](https://github.com/jingxueqing)
- 仓库：[jingxueqing/jingxueqing](https://github.com/jingxueqing/jingxueqing)

---

<sub>这个仓库的 README 会显示在我的 GitHub 主页顶部（profile README）。</sub>
