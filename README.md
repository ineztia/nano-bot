# nano-bot

AI 辅助任务执行系统，通过 AGENTS.md 指令驱动代理完成文件处理、知识获取、脚本执行与技能扩展等专业任务。

## 项目结构

```
nano-bot/
├── AGENTS.md         # 辅助任务系统提示词（角色定位、核心能力、执行原则）
├── .gitignore        # Git 忽略规则
├── logs/             # 任务执行日志
│   └── _expert-group/  # 专家合议组输出
└── tasks/            # 任务相关文件
```

## 核心能力

- **文件处理**：解析 .docx、.pptx、.xlsx、.pdf、图片等格式
- **知识获取**：联网查询、知识库检索、MCP 服务调用
- **脚本执行**：Python、Bash 等脚本自动化处理
- **技能扩展**：按需搜索、安装并调用专业 skill

## 使用方式

通过 Qoder / Claude 等 AI 代理加载此项目，AGENTS.md 将自动作为系统提示词生效。
