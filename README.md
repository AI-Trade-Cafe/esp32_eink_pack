# 學生包下載（v110）

**呢個 repo 只係派發學生包**——冇源碼、冇歷史。源碼（私人）：

> `github.com/AI-Trade-Cafe/esp32_eink`（私人，要導師加你入去才 clone 得到）

## 下載

撳下面個 zip，**唔使登入 GitHub**：

### 👉 [ESP32_eInk_StudentPack_v110.zip](https://github.com/AI-Trade-Cafe/esp32_eink_pack/releases/download/v110/ESP32_eInk_StudentPack_v110.zip)（91.5 MB）

或者去 [Releases 頁](https://github.com/AI-Trade-Cafe/esp32_eink_pack/releases) 揀版本。

## 解壓之後點做（Windows）

| 想做乜 | 雙擊 | 時間 |
|---|---|---|
| **改你屋企 WiFi** | `set-wifi.bat` | 約 1 分鐘（USB 寫入，唔使 compile） |
| 重燒機（預設 WiFi） | `flash.bat` → 打 `1` | 約 1 分鐘 |

Mac：`set-wifi-mac.command` / `flash-mac.command`（解壓後如話冇權限，見 `START-HERE.txt` 用 Terminal `bash` 方法）。

## 注意

- WiFi **一定要 2.4GHz**，ESP32 唔支援 5GHz。
- 包內**冇** `config.h`、**冇** `.git` —— 你嘅 WiFi 名／密碼只會寫入你自己部板，唔會上載去任何地方。
- 燒完睇屏幕右上角版本號：**v110** = 最新。
- 想自己改 firmware（巴士路線／站／方向／市場 symbols）→ 同導師攞私人 repo 權限，跟 `docs/CUSTOMIZE.md` 做。

## 版本

| 版本 | 內容 | 日期 |
|---|---|---|
| v110 | 巴士頁改九巴 2X 往彩福邨（新蒲崗譽．港灣）；`tools/flash-2x.bat` | 2026-11-14 |
| v109 | 學員 WiFi 經 USB 寫入 NVS（`set-wifi.bat`，免 compile） | 2026-10-21 |
