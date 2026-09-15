<div align="center">

# Hi, I'm ilylty

*Security Researcher · Reverse Engineering · Chromium/V8 Internals · AI Agent Automation*

[![Blog](https://img.shields.io/badge/Blog-paperBlog-2ea44f?style=flat-square&logo=githubpages&logoColor=white)](https://ilylty.github.io/paperBlog/)
[![Email](https://img.shields.io/badge/Email-ilylty%40qq.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ilylty@qq.com)

</div>

---

## <img src="https://img.shields.io/badge/-2ea44f?style=flat-square&logo=aboutdotme&logoColor=white" height="20" /> 关于我

- <img src="https://img.shields.io/badge/-4285F4?style=flat-square&logo=googlescholar&logoColor=white" height="16" /> 专注于 **Web / 移动端反爬对抗**、**浏览器指纹与签名参数逆向**、**JS 虚拟机保护与补环境** 方向
- <img src="https://img.shields.io/badge/-2088FF?style=flat-square&logo=githubactions&logoColor=white" height="16" /> 擅长把零散的逆向经验 **沉淀为可复用的自动化流水线**，用 AI Agent 替代重复的人工分析
- <img src="https://img.shields.io/badge/-34A853?style=flat-square&logo=android&logoColor=white" height="16" /> 涉猎 **Chromium 内核改造**、**Android 内核 / eBPF 动态插桩**
- <img src="https://img.shields.io/badge/-3776AB?style=flat-square&logo=python&logoColor=white" height="16" /> 主力语言：**Python · Go · Rust · TypeScript**，兼顾前端与 Cloudflare Workers 边缘部署

---

## <img src="https://img.shields.io/badge/-f97316?style=flat-square&logo=owasp&logoColor=white" height="20" /> 技能栈

<div align="center">

**逆向与安全**

![Reverse Engineering](https://img.shields.io/badge/Reverse_Engineering-★★★-critical?style=flat-square)
![Chromium](https://img.shields.io/badge/Chromium_Internals-4285F4?style=flat-square&logo=googlechrome&logoColor=white)
![V8](https://img.shields.io/badge/V8_/_JSVM-4B8BBE?style=flat-square&logo=v8&logoColor=white)
![CDP](https://img.shields.io/badge/CDP-40B5A4?style=flat-square&logo=puppeteer&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF_/_Kernel-FF6F00?style=flat-square&logo=linux&logoColor=white)
![IDA](https://img.shields.io/badge/IDA_Pro-6A1B9A?style=flat-square)
![Frida](https://img.shields.io/badge/Frida-FF3E3E?style=flat-square)

**语言与工程**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

**AI 与基础设施**

![AI Agent](https://img.shields.io/badge/AI_Agent_Workflow-412991?style=flat-square&logo=anthropic&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</div>

---

## <img src="https://img.shields.io/badge/-6f42c1?style=flat-square&logo=github&logoColor=white" height="20" /> 项目经历

### <img src="https://img.shields.io/badge/-4285F4?style=flat-square&logo=googlechrome&logoColor=white" height="20" /> AI Agent 通用浏览器环境签名参数自动化还原

> `2026-09` ～ `2026-09` · **核心研发**

**技术栈：** `Chromium 内核修改` · `BOM Tracing` · `JS 补环境` · `AI Agent`

**架构设计**

针对现代 Web / 小程序端复杂 VM 混淆与浏览器指纹校验的反爬机制，设计了一套基于 **AI Agent 驱动**的自动化补环境参数还原流水线。

**底层追踪与环境模拟**

- 通过**修改 Chromium 浏览器内核**实现 BOM 属性与 API 调用的 Trace
- 提出并落地通用性强的 **环境沙盒模拟 + 动态排除** 策略

**AI Agent 流水线与成本优化**

- 抽象逆向经验并固化为**标准化 AI Agent 执行工作流**，设计针对代码还原、环境校验断点定位的高效 Prompt 策略链
- AI Agent 仅调用轻量级模型（**DeepSeek-V4-Flash**），实现无人工介入修改代码的自动化分析

**项目成果**

| 维度 | 成果 |
| :--- | :--- |
| <img src="https://img.shields.io/badge/-FF6F61?style=flat-square&logo=rocket&logoColor=white" height="16" /> **极速交付** | 5 天内完成原型验证与方法论沉淀；在头部社交图文平台的实战验证中，仅耗时 **2 小时**即全自动化还原其端到端签名机制 |
| <img src="https://img.shields.io/badge/-10b981?style=flat-square&logo=target&logoColor=white" height="16" /> **高通用性** | 先后成功覆盖校园认证系统、复杂前端签名校验系统及头部互联网平台核心风控参数，验证了该方案的**高通用度与可复现性** |

---

## <img src="https://img.shields.io/badge/-ea4335?style=flat-square&logo=gmail&logoColor=white" height="20" /> 联系方式

- <img src="https://img.shields.io/badge/-ea4335?style=flat-square&logo=gmail&logoColor=white" height="16" /> Email：`ilylty@qq.com`
- <img src="https://img.shields.io/badge/-2ea44f?style=flat-square&logo=githubpages&logoColor=white" height="16" /> Blog：<https://ilylty.github.io/paperBlog/>
