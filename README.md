# WPM Monitor

**Typing analytics for Windows · Windows 打字效能分析工具**

[![Version](https://img.shields.io/badge/Version-1.0.0-blue)](https://github.com/balla0603/WPM-Monitor/releases)
![Platform](https://img.shields.io/badge/Platform-Windows%20x64-0078D4)
![Distribution](https://img.shields.io/badge/Distribution-Portable-lightgrey)

[繁體中文](#繁體中文) · [English](#english) · [Releases](https://github.com/balla0603/WPM-Monitor/releases) · [Issues](https://github.com/balla0603/WPM-Monitor/issues)

WPM Monitor 是一款 Windows 打字效能分析工具，於日常使用電腦時自動統計打字速度、修正率及長期表現，無須另外進行打字測驗。

### 功能

- 即時 WPM、KPM、原始及淨打字速度。
- 退格修正次數、修正率與估算準確率。
- 速度中位數、P90、持續打字峰值及有效打字時間。
- 每日、近 7 日及近 30 日統計與趨勢圖。
- 可調整連續打字間隔門檻。
- 系統匣背景執行、暫停與繼續監測。
- CSV 資料匯出、深淺色主題、高 DPI 顯示。

### 使用方式

1. 前往 [Releases](https://github.com/balla0603/WPM-Monitor/releases) 下載 Windows x64 版本（附件上傳後提供）。
2. 若下載 ZIP，先解壓縮，再執行 EXE。
3. 正常使用電腦即可累積統計。
4. 點擊主視窗右上方的「隱藏至系統匣」，可繼續背景監測。

### 統計指標

| 指標 | 說明 |
| --- | --- |
| Gross WPM | 原始打字速度 |
| Net WPM | 扣除估算修正量後的速度 |
| KPM | 每分鐘有效按鍵數 |
| Accuracy | 估算準確率 |
| Correction Rate | 修正率 |
| Median / P90 | 速度中位數及第 90 百分位 |
| Peak WPM | 持續打字峰值速度 |
| Active Time | 有效打字時間 |

WPM 以每五次有效輸入按鍵為一個標準字，依有效打字時間計算；中文輸入採按鍵速度估算。

### 系統需求

Windows 10 / 11（64 位元）。可攜式執行檔，無須安裝 PowerShell 腳本。執行檔尚未數位簽署。

WPM Monitor is a Windows typing analytics tool that automatically tracks typing speed, correction rates, and long-term typing performance during everyday computer use, without requiring dedicated typing tests.

### Features

- Real-time WPM, KPM, gross and estimated net typing speed.
- Backspace counts, correction rates, and estimated accuracy.
- Median WPM, P90, sustained peak speed, and active typing time.
- Daily, 7-day, and 30-day statistics and trends.
- Adjustable active typing interval threshold.
- System tray monitoring with pause and resume controls.
- CSV export, light and dark themes, and high-DPI display support.

### Getting started

1. Download the Windows x64 package from [Releases](https://github.com/balla0603/WPM-Monitor/releases) once the release assets are available.
2. Extract the ZIP if applicable and launch the executable.
3. Use your computer normally to accumulate typing statistics.
4. Use the top-right tray button to hide the window and continue monitoring.

### Metrics

| Metric | Description |
| --- | --- |
| Gross WPM | Gross typing speed |
| Net WPM | Estimated speed after corrections |
| KPM | Effective keystrokes per minute |
| Accuracy | Estimated typing accuracy |
| Correction Rate | Rate of corrections |
| Median / P90 | Median and 90th-percentile speed |
| Peak WPM | Sustained peak typing speed |
| Active Time | Active typing duration |

WPM uses five effective keystrokes per standard word and active typing duration. For Chinese input methods, WPM is a keystroke-based estimate.

### System requirements

Windows 10 / 11 (64-bit). Portable executable; no PowerShell script installation required. The executable is currently unsigned.

## Feedback｜問題回報

[Report a bug or request a feature｜回報問題或提出功能建議](https://github.com/balla0603/WPM-Monitor/issues/new/choose)

[Changelog｜版本紀錄](CHANGELOG.md)
