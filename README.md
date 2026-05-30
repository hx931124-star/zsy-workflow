# 一站式中实仪 · Agent Skills 工作流

中实仪新媒体内容生产的 Agent Skill 集合。审稿 → 发布，形成闭环。

## 📦 包含的 Skills

| Skill | 功能 | 触发 |
|-------|------|------|
| `zsy-review` | 七步审稿（客户画像/立场/聚焦/漏斗/行动/节奏/仪器闭环） | 「审稿」「看下这个脚本」 |
| `zsy-post` | 按四种账号风格生成发布短文案 | 「出发布文案」 |

## 🚀 安装到你的 Agent

### Claude Code / Codex / OpenClaw 等支持 SKILL.md 的 Agent

直接放到 skills 目录即可自动加载：

```bash
# 整库 clone
git clone https://github.com/hx931124-star/zsy-workflow.git ~/zsy-workflow

# 创建软链接（推荐，方便 git pull 更新）
ln -s ~/zsy-workflow/skills/zsy-review ~/.claude/skills/zsy-review
ln -s ~/zsy-workflow/skills/zsy-post ~/.claude/skills/zsy-post

# 或者直接复制
cp -r ~/zsy-workflow/skills/zsy-review ~/.claude/skills/
cp -r ~/zsy-workflow/skills/zsy-post ~/.claude/skills/
```

### 更新

```bash
cd ~/zsy-workflow && git pull
```

## 📄 License

MIT
