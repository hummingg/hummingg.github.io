独立开发者。我在做鸿蒙和浏览器工具，也研究 AI Agent、模型网关和可以运行小应用的手表。这里可以按用途查找我的公开 GitHub 仓库。文章和开发笔记在 [hummingg.com](https://www.hummingg.com/)；想看手表应用，可以去 [HumminggOS 项目站](https://watch.hummingg.com/)。

**2026-11-06 盘点：48 个公开仓库，含 17 个非 Fork 仓库、31 个 Fork。**「Fork」表示从上游项目派生，不代表上游由我维护。目录仅覆盖 `hummingg` 个人账号的公开仓库，不含私有和组织仓库。实时清单见 [GitHub 仓库列表](https://github.com/hummingg?tab=repositories)。

## 浏览器扩展

- **小红书对话链增强（XHS Thread Tracer）** — 把小红书评论区的楼中楼整理成对话树，方便看清谁在回复谁。[Chrome 网上应用店](https://chromewebstore.google.com/detail/%E5%B0%8F%E7%BA%A2%E4%B9%A6%E5%AF%B9%E8%AF%9D%E9%93%BE%E5%A2%9E%E5%BC%BA-xhs-thread-trace/ookblojepeokiceijhchckiekakiiebi?hl=zh-CN)
- **更多 Edge 扩展** — [在 Microsoft Edge 加载项商店浏览 hummingg 发布的扩展](https://microsoftedge.microsoft.com/addons/search?hl=zh-CN&developer=hummingg)。上架清单以商店为准，不限于下方的公开源码仓库。

## 项目与学习实践

### 应用与小工具

- **[harmonyos-hotspot-cards](https://github.com/hummingg/harmonyos-hotspot-cards)** — 原生鸿蒙手机开房，其他玩家用浏览器加入；在离线局域网里玩斗地主或掼蛋。
- **[MyPinyinIME](https://github.com/hummingg/MyPinyinIME)** — 面向 HarmonyOS 6 的原生离线九宫格拼音输入法，定位是个人使用。
- **[xhs-thread-tracer](https://github.com/hummingg/xhs-thread-tracer)** — Chrome 扩展，把小红书评论区的楼中楼还原成对话树，方便顺着上下文阅读。
- **[myllm-gateway](https://github.com/hummingg/myllm-gateway)** — 可自托管的多模型网关，统一管理不同供应商，并按标签或额度策略选择模型。
- **[Calculator](https://github.com/hummingg/Calculator)** — 一个浏览器计算器小项目，包含独立的帮助页。
- **[HumminggPassword](https://github.com/hummingg/HumminggPassword)** — Android 密码管理练习，包含密码生成、检索和加密文件导入导出；不作为安全背书。
- **[hummingg.github.io](https://github.com/hummingg/hummingg.github.io)** — 本站源码，维护项目目录和两份浏览器扩展的隐私政策。

### 给开发 Agent 的操作指南

- **[harmonyos-local-app-skill](https://github.com/hummingg/harmonyos-local-app-skill)** — 给鸿蒙开发新手的 Agent Skill，覆盖本地构建、调试签名和 USB 真机验证。
- **[nekobox-harmony-install-skill](https://github.com/hummingg/nekobox-harmony-install-skill)** — 从源码构建 NekoBox4Harmony，并安装到原生鸿蒙真机的操作指南。
- **[tailmesh-harmony-install-skill](https://github.com/hummingg/tailmesh-harmony-install-skill)** — 从源码构建 TailMesh（Tailscale 鸿蒙客户端）并安装到真机的操作指南。
- **[nas-ssh-ops-skill](https://github.com/hummingg/nas-ssh-ops-skill)** — 通过 SSH 维护 NAS 的 Agent Skill，涵盖密钥登录、批量操作、脱敏、备份与差异核对。
- **[tailscale-mac-nas-setup-skill](https://github.com/hummingg/tailscale-mac-nas-setup-skill)** — 在 Mac 和 NAS 上安装 Tailscale 并组网，包含 Docker 状态持久化等配置要点。

### 算法、设计模式与工程练习

- **[Vue](https://github.com/hummingg/Vue)** — 用网页演示常见排序算法和八皇后等问题；这是算法可视化项目，不是 Vue.js 框架仓库。
- **[LeetCode](https://github.com/hummingg/LeetCode)** — LeetCode 解题代码，以自己的解法为主，也记录了少量参考解法。
- **[DesignPattern](https://github.com/hummingg/DesignPattern)** — 用 C# 实现 27 种设计模式的练习。
- **[Front-End](https://github.com/hummingg/Front-End)** — 早期浏览器脚本和前端练习，包含简历助手及一个简易 MVVM 框架。
- **[gulimall](https://github.com/hummingg/gulimall)** — 谷粒商城课程实践，包含商品、会员、订单、库存等模块及管理端代码。

## Fork 与参考项目

### AI Agent、MCP 与模型接入

- **[mcp-node](https://github.com/hummingg/mcp-node)** — Node.js 聊天示例：通过 MCP 调用外部工具，在对话界面查看结果。
- **[claude-code](https://github.com/hummingg/claude-code)** — Anthropic 的终端编程 Agent 仓库，用于理解代码库和执行开发任务。
- **[deepseek-harness](https://github.com/hummingg/deepseek-harness)** — DeepSeek 的 Agent 运行框架，以插件组织功能，提供 Web 界面。
- **[hermes-agent](https://github.com/hummingg/hermes-agent)** — Nous Research 的个人 Agent 项目，可作为工具调用与跨会话工作流的参考。
- **[openclaw](https://github.com/hummingg/openclaw)** — 可自行运行的个人 AI 助手，连接不同消息渠道与工具。
- **[pi](https://github.com/hummingg/pi)** — 编程 Agent 工具包，包含统一模型接口、Agent 运行时、终端界面和 CLI。
- **[litellm](https://github.com/hummingg/litellm)** — 把不同供应商的模型接入统一的 OpenAI 风格接口，提供 Python SDK 和代理服务。

### 机器人与嵌入式

- **[ESP32-S3-Touch-AMOLED-2.06](https://github.com/hummingg/ESP32-S3-Touch-AMOLED-2.06)** — 微雪 2.06 英寸 ESP32-S3 触屏开发板的工程示例；不是 HumminggOS 固件仓库。
- **[ros2](https://github.com/hummingg/ros2)** — ROS 2 上游项目入口，汇集构建与获取 ROS 2 所需的仓库清单和说明。
- **[d2l-ros2](https://github.com/hummingg/d2l-ros2)** — 鱼香 ROS《动手学 ROS 2》课程的配套教程。
- **[lerobot](https://github.com/hummingg/lerobot)** — Hugging Face 的机器人学习工具，面向机器人数据与控制策略的训练和使用。
- **[every-embodied](https://github.com/hummingg/every-embodied)** — 从 Python 起步的具身智能教程，串联机器人项目和 OpenVLA、SmolVLA 等视觉语言动作模型。

### 网关、服务器与存储

- **[apisix](https://github.com/hummingg/apisix)** — Apache APISIX，面向云原生场景的 API 与 AI 网关。
- **[kong](https://github.com/hummingg/kong)** — Kong 网关，提供 API 路由和插件扩展，也面向 AI 请求代理场景。
- **[nginx](https://github.com/hummingg/nginx)** — NGINX 开源服务器源码，可作 Web 服务、反向代理与负载均衡参考。
- **[openresty](https://github.com/hummingg/openresty)** — 把 NGINX 与 LuaJIT 结合，用 Lua 扩展 Web 服务和网关逻辑。
- **[alist](https://github.com/hummingg/alist)** — 将多种存储接入统一网页界面的文件列表工具，使用 Gin 和 SolidJS。

### 输入法、翻译与编辑器工具

- **[qingjian](https://github.com/hummingg/qingjian)** — 用 Rust 编写的青简拼音输入法，在候选词旁显示正在学习的语言的译词。
- **[YuyanIme](https://github.com/hummingg/YuyanIme)** — 基于 Rime 的雨燕拼音输入法，包含九键、全拼、双拼等输入方案。
- **[MyTranslator](https://github.com/hummingg/MyTranslator)** — 基于百度翻译 API 的网页工具，支持翻译改写和文本对比。
- **[UniTranslate](https://github.com/hummingg/UniTranslate)** — Go 编写的翻译接入平台，把不同翻译服务收口到统一 API。
- **[LuaPanda](https://github.com/hummingg/LuaPanda)** — 面向 VS Code 的 Lua 调试与代码辅助工具。
- **[leetcode-cli](https://github.com/hummingg/leetcode-cli)** — 在终端里浏览题目、编写和提交 LeetCode 解答的工具。
- **[vscode-leetcode](https://github.com/hummingg/vscode-leetcode)** — 在 VS Code 中浏览并解答 LeetCode 题目的扩展。

### 课程、面试与全栈示例

- **[go-by-example](https://github.com/hummingg/go-by-example)** — Go 入门配套实例，包含猜谜游戏、命令行词典和 SOCKS5 代理。
- **[golang_note](https://github.com/hummingg/golang_note)** — Go 语言学习笔记的 Markdown 仓库。
- **[gulimall-learning](https://github.com/hummingg/gulimall-learning)** — 2020 年谷粒商城课程的代码与笔记参考。
- **[tiktok](https://github.com/hummingg/tiktok)** — 青训营极简抖音后端示例，使用 Kitex RPC 和 Hertz HTTP；不是抖音官方源码。
- **[zhengAdmin](https://github.com/hummingg/zhengAdmin)** — 基于 Bootstrap 的响应式后台管理界面，采用 Material Design 风格。
- **[interview-guide](https://github.com/hummingg/interview-guide)** — 面向后端开发校招的面试知识点整理。
- **[Markdown-Resume](https://github.com/hummingg/Markdown-Resume)** — 可复制修改的技术岗位 Markdown 简历模板。
