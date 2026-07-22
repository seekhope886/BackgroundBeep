# BackgroundBeep Extension for MIT App Inventor

這是一個輕量級的 MIT App Inventor 非可見元件擴展，透過 Android 的 `ToneGenerator` 播放 **10 種不同的系統級短促蜂鳴聲 (Beep) 與警示音**。無需額外的音效檔案，直接透過通知流播放，非常適合用於定時器、通知或遊戲事件。

## 🚀 功能特色

* **10 種內建音效**：包含短促聲、雙聲、確認/錯誤聲、DTMF 鍵盤音。
* **音量控制**：動態調整播放音量 (0–100)。
* **播放與停止**：可即時播放或立即停止音效。
* **SoundPlayed 事件**：成功播放時觸發，回傳音效類型索引。
* **無需音效資源**：極小化 `.apk` 體積（擴展大小約 3Kb）。
* **設計器屬性**：直接在 AI2 設計器中設定預設 `SoundType` 與 `Volume`。

## 🛠️ 屬性 (Properties)

| 屬性 | 類型 | 預設 | 描述 |
| :--- | :--- | :--- | :--- |
| `SoundType` | 數字 | `1` | 音效類型索引 (1–10)。 |
| `Volume` | 數字 | `50` | 播放音量大小 (0–100)。 |
<img width="203" height="59" alt="blocks1" src="https://github.com/user-attachments/assets/71d3dbe3-0bc0-4c6f-9bd6-9b108ac5cbdd" />

## 📦 方法 (Methods)

* **`Play()`**: 播放目前設定的 `SoundType`。
<img width="137" height="33" alt="blocks2" src="https://github.com/user-attachments/assets/2ee0f2ba-c2ef-4019-9d45-971c3a9febe2" />
* **`PlaySoundType(type)`**: 直接播放指定的音效索引 (1–10)。
<img width="192" height="46" alt="blocks3" src="https://github.com/user-attachments/assets/34296086-4a0f-4d6c-b37d-717b0cb94e0e" />
* **`Stop()`**: 立即停止目前播放的音效。

## 🔔 事件 (Events)

* **`SoundPlayed(type)`**: 音效開始播放後觸發。返回音效類型 `type`。

## 🎵 音效類型索引對照表 (Sound Map)

| 索引 | 音效描述 |
| :---: | :--- |
| **1** | 短促標準音 |
| **2** | 雙聲提示 |
| **3** | 確認提示音 |
| **4** | 錯誤警示音 |
| **5** | 網路忙線 / 插撥音 |
| **6** | 短促確認音 |
| **7** | 鍵盤音 1 |
| **8** | 鍵盤音 2 |
| **9** | 通知聲 |
| **10** | 低電量警告風格 |

## 📥 安裝與使用

1. 從 [MIT App Inventor 社群論壇](https://community.appinventor.mit.edu/t/free-backgroundbeep-short-alert-sound-for-mit-app-inventor/174491) 下載最新的 `.aix` 檔案。
2. 在 MIT App Inventor 專案中，切換到 **Palette** > **Extension** > **Import extension**。
3. 將 **BackgroundBeep** 元件拖放到 Viewer 中。

## 📄 授權與 credits

* **開發者**: luckyh9h
===================================================================================================================================
# BackgroundBeep Extension for MIT App Inventor

A lightweight non-visible extension for MIT App Inventor that plays **10 different system-level short beeps and alert sounds** using Android's `ToneGenerator`. No external audio assets needed. It plays through the notification stream, making it perfect for timers, notifications, or game events.

## 🚀 Features

* **10 Built-in Sounds**: Includes short beeps, double beeps, confirmation/error tones, and DTMF key tones.
* **Volume Control**: Dynamically adjust playback volume (0–100).
* **Play & Stop**: Instantly play sounds or stop them immediately.
* **SoundPlayed Event**: Triggers on successful playback, returning the sound type index.
* **Zero Asset Size**: Minimizes `.apk` file size (Extension is only around 3Kb).
* **Designer Properties**: Set default `SoundType` and `Volume` directly in the AI2 Designer.

## 🛠️ Properties

| Property | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| `SoundType` | Number | `1` | The index of the sound type (1–10). |
| `Volume` | Number | `50` | The playback volume level (0–100). |

## 📦 Methods

* **`Play()`**: Plays the currently configured `SoundType`.
* **`PlaySoundType(type)`**: Instantly plays a specific sound index (1–10).
* **`Stop()`**: Immediately stops the currently playing sound.

## 🔔 Events

* **`SoundPlayed(type)`**: Triggers after a sound starts playing. Returns the sound `type` index.

## 🎵 Sound Type Index Map

| Index | Sound Description |
| :---: | :--- |
| **1** | Short Standard Beep |
| **2** | Double Beep Alert |
| **3** | Confirmation Tone |
| **4** | Error Alert Tone |
| **5** | Network Busy / Call Waiting Tone |
| **6** | Short Acknowledgement Beep |
| **7** | Keypad Tone 1 |
| **8** | Keypad Tone 2 |
| **9** | Notification Sound |
| **10** | Low Battery Warning Style Tone |

## 📥 Installation & Usage

1. Download the latest `.aix` file from the [MIT App Inventor Community Thread](https://mit.edu).
2. In your MIT App Inventor project, navigate to **Palette** > **Extension** > **Import extension**.
3. Drag and drop the **BackgroundBeep** component into your Viewer.

## 📄 License & Credits

* **Developer**: luckyh9h
* **Release Date**: July 8, 2026
* **License**: Free for personal and commercial App Inventor projects. Please attribute the original thread link if shared.

* **發布日期**: 2026 年 7 月 8 日
* **授權**: 免費適用於個人及商業 App Inventor 專案。轉載請標註原連結。
