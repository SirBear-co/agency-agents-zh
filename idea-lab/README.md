# Idea Lab

一个用于收集灵感、选择合适 agent 讨论、并把讨论结果沉淀为文档的工作仓库。

## 适合放什么

- 突发奇想的内容账号 idea
- 产品、服务、品牌、课程、工具的雏形
- 还不够成熟，不值得单独开仓库的想法
- 需要和不同 agent 来回讨论、逐步成形的主题

## 工作流

1. 想法刚出现时，先记到 `inbox/`
2. 准备认真推进时，在 `projects/` 新建一个项目目录
3. 参考 `agents/agent-picking-guide.md` 选合适的 agent 讨论
4. 把讨论过程记到 `discussion.md`
5. 把稳定结论拆到 `outputs/` 下的独立文档
6. 需要继续推进时，再从这里毕业成独立仓库

## 新 Idea 的标准操作

当你冒出一个新想法时，按这个顺序处理就够了：

1. 先在 `inbox/` 新建一条记录
2. 用一句话写清“这是什么”
3. 补 3 到 5 条：我为什么想做、我最在意什么、我不想做成什么样
4. 去 `agents/agent-picking-guide.md` 找最接近当前问题的 agent
5. 在对话里先把想法聊清楚，不急着一次定完
6. 觉得值得继续时，在 `projects/` 下建正式目录
7. 把讨论沉淀为 `brief.md`、`discussion.md`、`outputs/` 和 `meta.yaml`
8. 后续每次推进，只更新项目目录，不要把结论继续散落在聊天记录里

### 一个最轻的判断标准

如果想法还很模糊：

- 先放 `inbox/`

如果已经开始有明确方向：

- 建 `projects/<slug>/`

如果已经产出稳定结论：

- 拆到 `outputs/`

### 每次都可以问自己的 3 个问题

- 我现在最卡的是内容、用户、品牌，还是执行？
- 这一步最适合找哪个 agent？
- 这次讨论结束后，什么内容值得沉淀成文档？

## 目录说明

```text
idea-lab/
├─ README.md
├─ inbox/
├─ projects/
├─ templates/
└─ agents/
```

### `inbox/`

放最原始的想法，不要求结构完整，只要求能快速记下来。

### `projects/`

每个成熟一点的 idea 一个目录，建议至少包含：

- `brief.md`：原始问题、目标、边界、你不想做成什么样
- `discussion.md`：和 agent 的来回讨论记录
- `outputs/`：整理后的结论
- `meta.yaml`：状态、标签、关联 agent

### `templates/`

复制即可用的模板。

### `agents/`

记录不同类型 idea 应该先找哪些 agent。

## 建议规则

- `inbox/` 里允许模糊
- `projects/` 里尽量具体
- `discussion.md` 可以发散
- `outputs/` 只放整理后的结论
- 一个 idea 先在总仓库孵化，真的要落地时再拆 repo

## 第一个示例

已内置示例项目：

- `projects/xiaohongshu-solo-baby-europe/`

这个示例展示了如何把一句灵感，整理成账号定位、内容支柱、首批选题和 agent 讨论记录。
