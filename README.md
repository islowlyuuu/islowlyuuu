# Hi，我是islowly

一个正在往 **AI 全栈开发** 方向持续深入的开发者。  
我喜欢把技术落到具体业务里：从跨境电商 ERP、法律 Agent 工作台，到面向求职场景的 AI 简历优化工具，关注的不只是“能跑起来”，也包括数据口径、交互体验、边界条件和后续维护。

目前主要使用：

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django REST](https://img.shields.io/badge/Django_REST-092E20?style=flat-square&logo=django&logoColor=white)
![Vue 3](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=20232A)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

也在持续探索：

![LLM Application](https://img.shields.io/badge/LLM_Application-111827?style=flat-square)
![AI Agent](https://img.shields.io/badge/AI_Agent-4F46E5?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-7C3AED?style=flat-square)
![OpenAI-compatible](https://img.shields.io/badge/OpenAI--compatible-10A37F?style=flat-square&logo=openai&logoColor=white)
![SSE](https://img.shields.io/badge/SSE-0F766E?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-CA8A04?style=flat-square)
![Workflow Automation](https://img.shields.io/badge/Workflow_Automation-2563EB?style=flat-square)

---

## 我关注的方向

- **AI 应用工程化**：让模型能力真正接入产品流程，而不是停留在 Demo。
- **业务系统开发**：ERP、后台管理、数据分析、导入导出、权限控制、复杂筛选。
- **Agent 工具调用**：工具注册、权限门控、上下文组织、流式输出和可观测性。
- **开发效率工具**：用 AI 辅助阅读代码、梳理需求、生成测试、优化表达。
- **长期可维护性**：清晰的数据结构、稳定的接口边界、可复现的问题定位方式。

---

## 技术栈

### Backend

![Backend](https://skillicons.dev/icons?i=python,fastapi,django,postgres,mysql,sqlite,docker,git)

### Frontend

![Frontend](https://skillicons.dev/icons?i=vue,react,nextjs,ts,js,tailwind,html,css)

### AI & Tools

![OpenAI API](https://img.shields.io/badge/OpenAI_API-10A37F?style=flat-square&logo=openai&logoColor=white)
![DeepSeek](https://img.shields.io/badge/DeepSeek-1E40AF?style=flat-square)
![Kimi](https://img.shields.io/badge/Kimi-6D28D9?style=flat-square)
![Qwen](https://img.shields.io/badge/Qwen-0F766E?style=flat-square)
![Claude Agent SDK](https://img.shields.io/badge/Claude_Agent_SDK-D97706?style=flat-square)
![Prompt Engineering](https://img.shields.io/badge/Prompt_Engineering-7C3AED?style=flat-square)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 近期项目

### AI Boss 投递助手

面向 Boss 直聘投递场景的 AI 简历优化工具。  
它不是生成一封很正式的求职信，而是帮助用户更快完成三件事：看懂岗位、改好简历、发出自然的第一句沟通。

- 使用 `Next.js`、`React`、`TypeScript`、`Tailwind CSS` 构建求职工作台。
- 基于 `FastAPI`、`SQLModel`、`SQLite` 实现分析记录、文件解析、方案保存和导出接口。
- 支持 PDF/DOCX 简历上传、JD 分析、匹配评分、ATS 关键词提取和经历 bullet 改写。
- 设计 `OpenAI-compatible Provider` 抽象，支持 `OpenAI`、`DeepSeek`、`Kimi`、`Qwen` 等模型配置。
- 在 API Key 缺失或模型请求失败时自动降级到本地关键词分析器，方便演示和离线测试。

### LexAgent AI 法律工作台

一个围绕法律案件材料处理的 AI Agent 工作台。  
我更关注其中的 Agent 运行链路：用户消息、工具注册、权限门控、LLM 推理、SSE 流式输出，以及案件级数据隔离。

- 新增案件材料统计工具，按 PDF、图片、音视频、文档等类型汇总材料状态。
- 优化工具调用事件的中文展示，避免前端直接暴露技术标识符。
- 调整系统 Prompt 结构，将角色、合规要求、技能和工具规则拆分得更清晰。
- 为权限门控补充测试，覆盖跨案件访问、工具白名单和 case_id 解析等场景。

### 跨境电商 ERP 系统

参与过真实业务 ERP 的前后端开发，覆盖订单、外采、供应商、物流费用、标签费、利润分析和报表导出等链路。

- 完善物流费、标签费、物料费、促销折扣、退款率等经营字段的导入、展示和导出。
- 支持利润分析 Excel 字段自选、选中货号导出、海关/规格字段扩展。
- 修复多平台订单时间、退款率、SKU/MSKU、运费分摊等数据口径问题。
- 补充供应商退货率、店铺状态导出、店铺被封时间等分析维度。

---

## 我的一些想法

我觉得 AI 对开发者最大的价值，不只是“帮我写代码”，而是让一个人能更快地理解陌生系统、拆解复杂问题，并把想法验证出来。

所以我会更在意这些问题：

- 这个功能是不是解决了真实场景里的问题？
- 数据从哪里来，口径是否一致，异常情况怎么处理？
- AI 生成的内容如何被约束、验证和回退？
- 项目能不能让别人快速运行、理解和继续维护？

比起追逐概念，我更希望自己能长期做出一些具体、有用、可迭代的东西。

---


---

## 联系我

- Email: `cikg0702@126.com`
- GitHub: [github.com/islowlyuuu](https://github.com/islowlyuuu)
