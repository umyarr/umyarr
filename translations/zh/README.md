🌐 [English](../../README.md) | [Русский](../ru/README.md)

# 罗曼·乌姆亚罗夫

构建解决实际问题的 AI 工具，并将其推向生产环境。

## 项目

**TvoyMeet** — 跨平台桌面应用（Win/Mac），用于会议转录。技术栈：faster-whisper + FFmpeg + customtkinter。输出结构化 .md 文件，可直接提交给 LLM。已打包为原生安装程序。

**NPS Feedback Analyst** — 三模式反馈分析流水线：本地 NLP（离线）、Gemini 2.5 Flash、Ollama。包含提示注入防护、MD5 缓存及 LLM 后数值验证。Telegram 机器人作为交互界面。

**Winx Bot** — aiogram 3 + GigaChat。读取团队聊天消息，提取任务，映射到负责人，将结构化 JSON 返回至指定话题。作为 systemd 服务运行于 VPS。

**FIFA26 Predictor** — 比赛结果预测的机器学习模型。

## 技术栈

`Python` `GigaChat` `GigaCode` `aiogram` `faster-whisper` `pandas` `REST API` `systemd` `PyInstaller`

## 关于我

从事青年政策工作——通过团队培训实现运营自动化与知识规模化。擅长将技术方案转化为非技术人员可理解并落地的实践。
