# 🐾 貓狗送養平台

一個簡潔清新的靜態網站，讓使用者可以瀏覽待認養的貓狗、刊登送養資訊、以及透過表單聯絡送養人。適合個人或小型動保團體展示送養資料。

---

## 🌟 功能特色

- 🐶 **待認養清單**：以卡片方式顯示動物圖片與基本資料。
- 🔍 **篩選功能**：可依照品種（貓/狗）與年齡分類顯示。
- 📝 **刊登送養表單**：管理員可上傳圖片、填寫基本資訊並即時顯示在清單中。
- 💬 **聯絡表單**：訪客可留下聯絡方式與訊息。
- 🖥️ **後台頁面（靜態展示）**：模擬審核與刪除送養資訊的管理介面。
- 📱 **RWD 響應式設計**：在手機、平板與桌機上皆能完美顯示。

---

## 🚀 GitHub Pages 部署教學

以下步驟可以讓你輕鬆把網站上傳並公開在 GitHub Pages：

### 1️⃣ 建立 GitHub Repository
1. 前往 [GitHub](https://github.com/)。
2. 登入後點選右上角「+」→ **New repository**。
3. 輸入 Repository 名稱，例如：`pet-adoption-site`。
4. 設定成 **Public**（公開）。
5. 點選 **Create repository**。

### 2️⃣ 上傳網站檔案
1. 下載你的網站檔案：
   - `index.html`（主頁面）
   - 任何圖片資料夾（若有）
2. 在 GitHub Repository 頁面中，點擊 **Add file → Upload files**。
3. 上傳上述檔案後，按下 **Commit changes** 儲存。

### 3️⃣ 啟用 GitHub Pages
1. 進入剛建立的 Repository。
2. 點選上方的 **Settings（設定）**。
3. 在左側選單找到 **Pages**。
4. Source 選項中選擇：
   - **Deploy from a branch**
   - **Branch：main / 根目錄 (/）**
5. 按下 **Save**。

GitHub 會自動幫你部署，幾分鐘後你會看到像這樣的網址：
```
https://你的帳號.github.io/pet-adoption-site/
```

🎉 **恭喜！你的送養網站已經上線！**

---

## 🧩 結構說明

```
pet-adoption-site/
│
├── index.html          # 主頁面（包含所有內容）
└── images/             # 動物圖片（可選）
```

所有功能都包含在單一 `index.html` 中，適合靜態主機或 GitHub Pages 使用。

---

## 🧰 未來可擴充方向

- ✉️ 將聯絡表單串接到 Formspree 或 Google Form。
- 💾 使用 Firebase 或 Airtable 儲存送養資料。
- 👩‍💻 加入簡易的登入系統供管理員審核。
- 🐕‍🦺 新增多語系（繁中、英語）。

---

## 🐱 授權條款
本專案可自由修改與使用，請保留原作者註記並勿用於商業詐騙或販售用途。

---

> ❤️ 由 ChatGPT 與你共同打造。讓愛延續每一個生命。
