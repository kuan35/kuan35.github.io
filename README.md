# kuan35.github.io

個人 GitHub Pages 網站，目前展示 Web3 區塊鏈技術實作。

---

## 🔗 Web3 DApp 測試頁

**網址：** [https://kuan35.github.io/test/](https://kuan35.github.io/test/)

### 專案說明

本頁面是一個部署在 **Ethereum Sepolia 測試網**上的智能合約互動介面，使用純前端技術（HTML + JavaScript）搭配 [ethers.js v6](https://docs.ethers.org/v6/) 實作，無需後端伺服器。

### 合約資訊

| 項目 | 內容 |
|------|------|
| 合約名稱 | `HelloWorld` |
| 網路 | Ethereum Sepolia Testnet |
| 合約地址 | [`0xFC5A0EDEb75a9FBd3fC9Af6F475AA02b904B4d92`](https://sepolia.etherscan.io/address/0xFC5A0EDEb75a9FBd3fC9Af6F475AA02b904B4d92) |
| 合約功能 | 讀取 / 更新鏈上訊息 |

### 功能介紹

- **連接 MetaMask** — 授權瀏覽器錢包，讀取當前帳戶地址
- **讀取訊息** — 呼叫 `message()` view function，從鏈上讀取當前儲存的字串（免 Gas）
- **更新訊息** — 呼叫 `updateMessage()` 發送鏈上交易，將新訊息寫入合約（需 Sepolia 測試幣）
- **交易日誌** — 即時顯示交易 Hash 及確認狀態

### 使用方式

1. 安裝 [MetaMask](https://metamask.io/) 瀏覽器擴充套件
2. 將網路切換至 **Sepolia 測試網**
3. 前往 [https://kuan35.github.io/test/](https://kuan35.github.io/test/)
4. 點擊「連接 MetaMask」，授權後即可讀取與更新鏈上訊息

> 若需要 Sepolia 測試幣，可至 [Alchemy Faucet](https://sepoliafaucet.com/) 或 [Chainlink Faucet](https://faucets.chain.link/sepolia) 免費領取。

### 技術棧

- **智能合約：** Solidity（部署於 Sepolia Testnet）
- **前端：** HTML5 / CSS3 / Vanilla JavaScript
- **區塊鏈 SDK：** ethers.js v6
- **錢包整合：** MetaMask（EIP-1193 Provider）
- **部署：** GitHub Pages

---

*由 kuan35 維護*
