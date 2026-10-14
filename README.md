### 👋 你好，我是 @b1789544020

主要开发方向：**LLM 应用 / Linux 系统编程 / 数据工具 / 浏览器扩展**。

做东西坚持自力更生：工具能离线的不依赖服务端，系统项目能零依赖的不引第三方库。

---

## 🐧 Linux 系统编程（手写内核机制，纯 Python 标准库）

| 项目 | 简介 | 技术栈 |
| --- | --- | --- |
| **[mini-docker](https://github.com/b1789544020-sys/mini-docker)** | 零依赖手写迷你容器运行时：6 种 namespace 隔离 / chroot 根文件系统 / cgroups v2 资源限额 / veth+bridge 容器网络，分课教学、每课可运行 | Linux Namespaces · cgroups v2 · veth/bridge |
| **[pulsewatch](https://github.com/b1789544020-sys/pulsewatch)** | 零依赖系统监控：不调用任何外部命令，直读 /proc 内核台账（CPU / 内存 / 磁盘 / 网络 / 进程），内置 Web 实时仪表盘 | /proc 直读 · asyncio · Web 仪表盘 |

## 🤖 LLM 应用

| 项目 | 简介 | 技术栈 |
| --- | --- | --- |
| **[agentforge](https://github.com/b1789544020-sys/agentforge)** | 可自托管的 Agent 后端框架：可观测的 Agent 循环（落库、暂停、恢复）、WebSocket 实时步骤流、沙箱工具、长期记忆、批量 eval 评测，285 项测试全绿 | FastAPI · SQLAlchemy · WebSocket · Docker |
| **[datasage](https://github.com/b1789544020-sys/datasage)** | 反幻觉数据分析引擎：自然语言 → LLM 生成 pandas → 受限沙箱执行 → 三层验证 → 答案数字逐个回溯溯源，幻觉自动拦截带证据重写（内置 mock LLM，零 API Key 可演示） | FastAPI · pandas · Vite · SQLite |
| **[SnapMark](https://github.com/b1789544020-sys/SnapMark)** | 截图 AI 浏览器插件：区域 / 整页滚动拼接 / 元素级截图、箭头马赛克序号标注，截图直接问视觉大模型（OCR、解释报错、翻译、转表格），流式输出 | Chrome MV3 · Canvas · Vision LLM |

## 📦 数据与效率工具

| 项目 | 简介 | 技术栈 |
| --- | --- | --- |
| **[DataForge Pro](https://github.com/b1789544020-sys/DataForge-Pro)** | 12 合 1 隐私优先数据工具箱：数据清洗 / 格式转换 / 多表合并去重 / 图片批处理 / 可选 AI 助手。内含**零依赖原生 xlsx 读写引擎**（基于 CompressionStream，不依赖 SheetJS） | 原生 JavaScript · AI Assistant |
| **[TableSniffer](https://github.com/b1789544020-sys/TableSniffer)** | Chrome 扩展：嗅探网页上的表格并导出 Excel / CSV，含测试、CI 与安全策略 | Chrome MV3 · DOM 解析 |
| **[DataHub](https://github.com/b1789544020-sys/DataHub)** | 本地工具产物的云端中转站：上传即得可分享短链，支持密码 / 过期时间 / 预览页，定时自动清理 | Node.js · Express · SQLite · Docker |

- **[ChartForge](https://github.com/b1789544020-sys/ChartForge)** — 浏览器内数据可视化看板：ECharts 图表、字段映射、导入向导、AI 图表推荐
- **[DataCleanerProAI](https://github.com/b1789544020-sys/DataCleanerProAI)** — CSV / Excel 清洗工具：13 项一键清洗规则 + 大模型辅助
- **[InvoiceForge](https://github.com/b1789544020-sys/InvoiceForge)** — 离线发票 / 单据生成器：周期账单、二维码、热敏打印、模板编辑器、本地加密

---

## 🗄 已归档

`FileMergerPro` 与 `imageforgepro` 的功能已并入 **DataForge Pro**；`ResumeForge`、`python-storybook` 已停止维护，仓库代码保留可查。
