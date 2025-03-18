---
theme: seriph
background: https://cover.sli.dev
title: 讓你事半功倍的 AI 工具
class: text-center
drawings:
  persist: false
transition: fade-out
mdc: true
---

# 讓你事半功倍的 AI 工具

AI-powered coding tools to supercharge your development workflow

---

# 聽完演講可以獲得什麼？

- 提升開發效率：掌握編輯器中的 AI 輔助工具（Continue）
- 深入理解 Model Context Protocol 及其應用

<div class="mt-8">
  <div class="mt-4 flex justify-center">
    <img src="/images/continue.png" class="rounded shadow-xl w-1/2" />
  </div>
  <div class="mt-4 flex justify-center">
    <img src="/images/mcp.webp" class="rounded shadow-xl w-1/2" />
  </div>
</div>


---

# 達哥 Web UI vs Continue

<div class="grid grid-cols-2 gap-4">
<div>
<h3>達哥 Web UI</h3>

- 適合公司各角色使用的網頁界面
- 支援上傳文件分析與處理
- 公司成員可互相分享對話、助理等
- 統一的企業知識庫

</div>
<div>
<h3>Continue VSCode</h3>

- 直接整合在開發環境中
- 深度理解你的程式碼結構與上下文
- 即時編輯與建議，無需切換窗口
- 專為開發者工作流程優化

</div>
</div>

---

# 什麼是 Continue？

Continue is the leading open-source AI code assistant inside VS Code and JetBrains, featuring:

- 💬 **Chat** - understand and iterate on code in the sidebar
- 🔮 **Autocomplete** - receive inline code suggestions as you type
- ✏️ **Edit** - modify code without leaving your current file
- ⚡ **Actions** - establish shortcuts for common use cases

---
layout: center
class: text-center
---

# 這 AI 功能公司內可用？沒資安風險？

---

# 安全考量

- 與達哥使用相同的 Azure Gateway
- 所有資料通過企業防火牆
- 程式碼不會離開公司網路環境
- 可配置敏感信息過濾

<br/>

> Continue 設定檔可參考 chatbot-ui repo 的 `.continuerc.json.example`

---

# How to use Chat？

1. Type a request and press enter
2. Highlight a code section to include as context
3. Reference context with the @symbol

---

# Context Provider

1. @File - 引用特定檔案
2. @Code - 引用程式碼片段
3. @Git Diff - 查看當前更改
4. @Current File - 使用目前檔案
5. @Terminal - 終端機輸出
6. @Docs - 文件內容
7. @Open - 已開啟檔案
8. @Web - 網頁內容
9. @Codebase - 整個程式碼庫
10. @Folder - 特定資料夾

更多 Context 參考 [Context providers](https://docs.continue.dev/customize/context-providers#context-blocks)

---

# 實用 Actions 功能

1. **Slash commands** (`/explain`, `/edit`)
2. **Prompt files** (預設提示模板)
3. **Right Quick actions** (右鍵選單)
4. **Quick fixes** (快速修復建議)

---

# Tools

Tools allow Continue to take action in your IDE and beyond (when you give permission)

Currently custom tools can be configured using the Model Context Protocol（MCP）

---
layout: center
class: text-center
---

# 那什麼是 MCP (Model Context Protocol)？

<br />

### 再來交給 **Flynn** 🔥