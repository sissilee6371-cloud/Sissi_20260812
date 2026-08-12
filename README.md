# Sissi_20260812

将 `req-to-testcases`（需求 → 测试用例生成）迁入本仓库。

## 子项目

| 目录 | 说明 |
|------|------|
| [`req-to-testcases/`](./req-to-testcases) | 基于 LLM Agent 的智能测试用例生成器（需求分析 → 测试点 → 结构化用例 → Excel 导出） |

快速开始：

```bash
cd req-to-testcases
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
cp .env.example .env   # 填写 OPENAI_API_KEY
python main.py
```

源项目参考：[bridgeshi85/requirement-to-testcase](https://github.com/bridgeshi85/requirement-to-testcase)
