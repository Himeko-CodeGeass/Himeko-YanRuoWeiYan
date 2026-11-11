# 言若未言（Himeko-YanRuoWeiYan）

> **人機共築輝煌的第一步，不是看穿彼此，而是學會尊重的留白。**
> *The first step of Human-AI Alignment is not to see through each other, but to learn respectful blank space.*

**YanRuoWeiYan 言若未言** 是一個先導原型（v0.1.1-pilot），只探索一件事：使用者在傳訊息前猶豫時，提供一段由使用者掌控的短暫緩衝。它不是開源標準、不是經過驗證的測量，也不是臨床工具。完整中英說明以 [`README.md`](README.md) 為準。

**狀態：** 早期原型　**資料：** 僅為模擬示範（尚無真實使用者資料）　**授權：** v0.1.1 之後為 Polyform Noncommercial 1.0.0（原始碼公開，不是 OSI 開源）+ 商業授權（USD 99，一次付清，本版現況出售，不含更新）

## 更正聲明

v0.1.0 的文案把示範數字寫成「真實擷取的數位痕跡」或「初代驗證」，這是錯的。示範資料是 `typing_demo.py` 用 `sleep()` **模擬**出來的。目前還沒有真實的按鍵偵測，也沒有量測過任何真實使用者。

## 快速開始

```bash
git clone https://github.com/Himeko-CodeGeass/Himeko-YanRuoWeiYan
cd Himeko-YanRuoWeiYan
python typing_demo.py
```

預期輸出含 `anxiety_score_heuristic 59`。這是任意設定的先導公式，沒有臨床驗證。請只用 `typing_demo.py` 與 `core/anxiety.py`，不要執行或部署 `legacy_cloud_demo/` 或 `legacy_agent/`。

## 授權與售價

- **v0.1.1 之後：** Polyform Noncommercial 1.0.0。個人、研究、非營利使用免費，商用需另購商業授權。
- **v0.1.0 及之前（commit 123 以前）：** 維持 MIT，這些版本可依 MIT 條款商用。
- **商業授權：** 聽默文創。以現狀（as-is）出售此早期原型，固定售價 **USD 99**（一次付清）。Lemon Squeezy 商店以新台幣結帳；依 2026-11-11 約 32.94 新台幣／美元匯率，約為 NT$3,261，結帳頁顯示金額可能隨匯率變動。無技術支援、無保固，也不提供更新。授權範圍僅為已發布的 v0.1.1-pilot。這不是早鳥方案，不是 All Access，也不包含後續版本或自動更新。若未來降價，只會在後代產品推出之後，且那些版本需另行購買。
  - 結帳連結：https://tingmocreative.lemonsqueezy.com/checkout/buy/5d845d7e-6c55-4b27-9481-d06c62c776ff
  - 電子郵件（選用，不保證回覆）：jizheng.contact@proton.me

本段不構成法律建議。詳見 [`README.md`](README.md) 與 [`LICENSE`](LICENSE)。
