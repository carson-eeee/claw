# 🤖 Clawdbot 操作手冊 (Linux 版)

## 🚀 啟動與停止
* `clawdbot gateway`          - 啟動 Gateway (連接 Discord/API)。
* `clawdbot gateway stop`     - 停止後台服務。
* `clawdbot gateway status`   - 檢查目前 Bot 係咪行緊。
* `clawdbot gateway restart`  - 重新啟動（改咗 Config 後必用）。

## ⚙️ 設定與維護
* `clawdbot onboard`          - 重新執行設定精靈（改 API Key 或 Channel）。
* `clawdbot doctor`           - 自動檢查系統環境有冇出錯。
* `clawdbot --version`        - 睇吓目前版本。
* `clawdbot logs --follow`    - 即時睇住個 Bot 做緊咩（除錯好有用）。

## 🛠️ 技能與插件 (Skills)
* `clawdhub list`             - 睇吓你裝咗啲咩技能。
* `clawdhub search <keyword>` - 搵吓有冇新功能裝。
* `clawdhub install <name>`   - 安裝新技能。

## 🛡️ 安全指令
* `clawdbot pairing list`     - 睇吓邊個 Discord User 攞咗授權。
* `clawdbot pairing approve <ID>` - 批准新的使用者。
* `pkill -f clawdbot`         - [緊急用] 強行關閉所有 Clawdbot 行程。

## 📁 重要路徑
* 設定檔位置：`~/.config/clawdbot/clawdbot.json`
* 數據儲存：`~/.clawdbot/`