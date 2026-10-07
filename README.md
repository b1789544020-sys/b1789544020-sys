### 👋 你好，我是 @b1789544020

主要开发方向：**数据工具 / 浏览器扩展 / LLM 应用**。

项目默认优先在浏览器本地运行，能离线使用的不依赖服务端和 API Key。

---

## 📦 主要项目

| 项目 | 简介 | 技术栈 |
| --- | --- | --- |
| **[DataForge Pro](https://github.com/b1789544020-sys/DataForge-Pro)** | 12 合 1 隐私优先数据工具箱：数据清洗 / 格式转换 / 多表合并去重 / 图片批处理 / 可选 AI 助手。内含**零依赖原生 xlsx 读写引擎**（基于 CompressionStream，不依赖 SheetJS） | 原生 JavaScript · AI Assistant |
| **[TableSniffer](https://github.com/b1789544020-sys/TableSniffer)** | Chrome 扩展：嗅探网页上的表格并导出 Excel / CSV，含测试、CI 与安全策略 | Chrome MV3 · DOM 解析 |
| **AgentForge** 🚧 | LLM Agent 设计 / 追踪 / 评测工作台：可观测的 Agent 循环（落库、暂停、恢复）、沙箱工具、长期记忆、批量评测打分 | FastAPI · React · Docker |
| **DataSage** 🚧 | 可信数据分析引擎：自然语言 → LLM 生成 pandas → **禁网沙箱执行** → 三层验证 → 答案数字逐字回溯，拦截并改写幻觉数字，内置 mock LLM 可离线演示 | FastAPI · Vite · SQLite |
| **SnapMark** 🚧 | 截图 AI 浏览器插件：区域 / 整页滚动拼接 / 元素级截图、箭头马赛克序号标注，截图直接问视觉大模型（OCR、解释报错、翻译、转表格），流式输出 | Chrome MV3 · Canvas · Vision LLM |
| **DataHub** 🚧 | 本地工具产物的云端中转站：上传即得可分享短链，支持密码 / 过期时间 / 预览页，定时自动清理 | Node.js · Express · SQLite · Docker |

> 🚧 = 本地开发中，尚未开源

---

## 🧰 其他工具

- **[ChartForge](https://github.com/b1789544020-sys/ChartForge)** — 浏览器内数据可视化看板：ECharts 图表、字段映射、导入向导、AI 图表推荐
- **[DataCleanerProAI](https://github.com/b1789544020-sys/DataCleanerProAI)** — CSV / Excel 清洗工具：13 项一键清洗规则 + 大模型辅助
- **[InvoiceForge](https://github.com/b1789544020-sys/InvoiceForge)** — 离线发票 / 单据生成器：周期账单、二维码、热敏打印、模板编辑器、本地加密

---

## 🗄 已归档

`FileMergerPro` 与 `imageforgepro` 的功能已并入 **DataForge Pro**；`ResumeForge` 已停止维护，仓库代码保留可查。
