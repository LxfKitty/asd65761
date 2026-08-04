CFnew 简洁毛玻璃 UI 视觉升级版

- 基于原项目技术体系：Cloudflare Worker + 原生 HTML/CSS/JavaScript。
- 仅在 HTML Response 层注入主题、视觉样式和轻量交互；节点、订阅、KV、API、路由与表单逻辑未重写。
- 支持跟随系统、浅色、深色三种主题，默认跟随系统。
- 主题选择保存在 localStorage：cfnew-theme-mode。
- 保留原有页面特效开关，改为控制新的克制动效。
- m 保持明文核心；s 保持原混淆核心；snippets 同步升级。
- 无新增依赖。
