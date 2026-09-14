# flowise-v3.0.5 - 漏洞总览

| # | CVE | 端点 | 漏洞类型 | 状态 |
|---|---|---|---|---|
| 1 | CVE-2025-58434 | `POST /api/v1/account/forgot-password` | 认证绕过 / 敏感信息泄露 (CWE-306) | 🔍 CODE_AUDIT |
| 2 | CVE-2025-59527 | `GET /api/v1/fetch-links` | 服务端请求伪造 (CWE-918) | 🔍 CODE_AUDIT |
| 3 | CVE-2025-59528 | `POST /api/v1/node-load-method/customMCP` | 代码注入 / 远程代码执行 (CWE-94) | 🔍 CODE_AUDIT |
| 4 | CVE-2025-71324 | `GET /api/v1/get-upload-file` | 路径遍历 / 任意文件读取 (CWE-22) | 🔍 CODE_AUDIT |
| 5 | CVE-2025-71334 | `GET /api/v1/get-upload-file` | 路径遍历 / 任意文件读写 (CWE-22) | 🔍 CODE_AUDIT |
| 6 | CVE-2025-71336 | `POST /api/v1/node-load-method/customMCP` | 命令注入 / 远程代码执行 (CWE-78, CWE-862) | 🔍 CODE_AUDIT |
| 7 | CVE-2025-8943 | `POST /api/v1/node-load-method/customMCP` | OS 命令注入 / 远程代码执行 (CWE-78) | 🔍 CODE_AUDIT |
