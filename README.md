
# 🤖 AI × Notion 自动摘要系统

## ✅ 功能说明
- 每天抓取 RSS 新闻
- 使用 OpenAI GPT 自动生成中文摘要
- 写入 Notion 数据库（你指定的表格页面）

## 🛠 部署前你需要准备
1. OpenAI API Key（来自 https://platform.openai.com/account/api-keys）
2. Notion API Token（来自 https://www.notion.so/my-integrations）
3. Notion 数据库 ID（你的 Notion 表格页面链接里的 ID）

## ⚙️ GitHub Secrets 需要设置以下 3 项
- `OPENAI_API_KEY`
- `NOTION_TOKEN`
- `NOTION_DAILY_SUMMARY_DB`

## 🚀 部署方式
1. 上传该项目文件到 GitHub 仓库
2. 配置 Secrets
3. 手动点击 Actions → Run Workflow
