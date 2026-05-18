# 📦 IconLibrary

個人 Emby 圖標庫，部分圖標同步自 [sooyaaabo/IconLibrary](https://github.com/sooyaaabo/IconLibrary)，並收錄自製圖標。

---

## 📋 圖標列表

👉 [查看完整圖標預覽 →](./Emby-Icons.md)

---

## 🗂 檔案說明

| 檔案 | 說明 |
|------|------|
| `Emby/` | 所有 Emby 圖標 PNG 檔 |
| `Emby-Icon.json` | 圖標 JSON（供 Emby 插件匯入） |
| `Emby-Icons.md` | 圖標預覽列表（自動生成） |

---

## 🔧 使用方法

在 Emby 插件中填入以下 JSON 連結：

```
https://raw.githubusercontent.com/stevendolike/IconLibrary/main/Emby-Icon.json
```

---

## 🤖 自動化說明

| Workflow | 觸發條件 | 說明 |
|----------|----------|------|
| `sync-upstream.yml` | 每天 港時 10:00 | 從上游同步新圖標到 `Emby/` |
| `update-icon-json.yml` | `Emby/` 有變動 | 更新 `Emby-Icon.json` 及 `Emby-Icons.md` |

---

## 📝 自定義圖標名稱

直接編輯 `Emby-Icon.json` 中對應的 `name` 欄位，workflow 重新執行時會保留你的修改。

---

*部分圖標來源：[sooyaaabo/IconLibrary](https://github.com/sooyaaabo/IconLibrary)*
