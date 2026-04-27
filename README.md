# Tab Close

> A clean new tab dashboard for **Microsoft Edge** and Chrome to organize tabs, close clutter, and manage quick todos.
>
> 适用于 **Microsoft Edge** 和 Chrome 的新标签页仪表盘——整理标签页、清理冗余、管理待办事项。
>
> **Microsoft Edge** と Chrome の新しいタブをダッシュボードに変え、タブ整理・クリーンアップ・Todo 管理を一画面で。

---

## Language / 语言 / 言語

- [English](#english)
- [中文](#中文)
- [日本語](#日本語)

---

## English

### What is Tab Close?

Tab Close replaces your new tab page in **Microsoft Edge** or Chrome with a minimal dashboard. It groups all your open tabs by domain, helps you spot and close duplicates, lets you save tabs for later, and includes a lightweight Todo list — all stored locally with no server or account required.

### Browser Compatibility

| Browser | Support |
|---|---|
| Microsoft Edge (Chromium) | ✅ Fully supported |
| Google Chrome | ✅ Fully supported |

### Features

| Feature | Description |
|---|---|
| **Tab Overview** | All open tabs grouped by domain in a bento-style card grid |
| **Duplicate Detection** | Highlights duplicate tabs within a domain and lets you close them in one click |
| **Close by Group** | Close all tabs in a domain group at once |
| **Save for Later** | Bookmark tabs to a persistent sidebar checklist without losing them |
| **Add to Todo** | Pin any tab's title as a todo item directly from its chip |
| **Todo List** | Right-side panel with add / complete / delete; persisted in `chrome.storage.local` |
| **Greeting & Date** | Time-aware greeting and today's date shown in the header |
| **Duplicate Tab Banner** | Auto-detects extra Tab Close tabs and offers to close the extras |
| **100% Local** | No network requests, no account, no telemetry |

### Installation

**Microsoft Edge**

1. Clone or download this repository
2. Open Edge and go to `edge://extensions/`
3. Enable **Developer mode** (bottom-left toggle)
4. Click **Load unpacked** and select the `extension/` folder
5. Open a new tab — Tab Close takes over

**Google Chrome**

1. Clone or download this repository
2. Open Chrome and go to `chrome://extensions/`
3. Enable **Developer mode** (top-right toggle)
4. Click **Load unpacked** and select the `extension/` folder
5. Open a new tab — Tab Close takes over

### Tech Stack

- Vanilla JS (ES2022) + HTML + CSS
- Chrome Extension Manifest V3 (compatible with Edge)
- `chrome.storage.local` for all persistence

### Credits

Built by [Yobot](https://github.com/yobotyao-maker)

### License

MIT

---

## 中文

### 什么是 Tab Close？

Tab Close 将 **Microsoft Edge** 或 Chrome 的新标签页替换为一个简洁的仪表盘。它按域名将所有打开的标签页分组显示，帮助你发现并关闭重复标签，支持将标签"稍后再看"，还内置了轻量级待办事项列表——所有数据均保存在本地，无需服务器或账号。

### 浏览器兼容性

| 浏览器 | 支持情况 |
|---|---|
| Microsoft Edge（Chromium 版） | ✅ 完全支持 |
| Google Chrome | ✅ 完全支持 |

### 功能特性

| 功能 | 说明 |
|---|---|
| **标签总览** | 所有打开的标签按域名分组，以卡片网格形式展示 |
| **重复检测** | 自动高亮同域名下的重复标签，一键关闭多余标签 |
| **按组关闭** | 一键关闭某个域名下的全部标签 |
| **稍后再看** | 将标签保存到右侧持久化清单，不关闭标签页也能随时找回 |
| **添加到待办** | 直接从标签片段将标题添加为待办事项 |
| **待办列表** | 右侧面板支持新增 / 完成 / 删除，数据持久化在 `chrome.storage.local` |
| **问候与日期** | 页头显示时段问候语和今日日期 |
| **重复标签横幅** | 自动检测多余的 Tab Close 标签页，提示一键关闭 |
| **完全本地** | 无网络请求，无账号，无数据上报 |

### 安装方法

**Microsoft Edge**

1. 克隆或下载本仓库
2. 打开 Edge，访问 `edge://extensions/`
3. 开启左下角的**开发人员模式**
4. 点击**加载解压缩的扩展**，选择 `extension/` 文件夹
5. 打开新标签页，即可看到 Tab Close 界面

**Google Chrome**

1. 克隆或下载本仓库
2. 打开 Chrome，访问 `chrome://extensions/`
3. 开启右上角的**开发者模式**
4. 点击**加载已解压的扩展程序**，选择 `extension/` 文件夹
5. 打开新标签页，即可看到 Tab Close 界面

### 技术栈

- 原生 JS（ES2022）+ HTML + CSS
- Chrome 扩展 Manifest V3（与 Edge 兼容）
- `chrome.storage.local` 负责所有数据持久化

### 致谢

作者：[Yobot](https://github.com/yobotyao-maker)

### 许可证

MIT

---

## 日本語

### Tab Close とは？

Tab Close は **Microsoft Edge** または Chrome の新しいタブページをミニマルなダッシュボードに置き換えます。開いているすべてのタブをドメイン別にグループ化し、重複タブの検出・削除、後で読むためのタブ保存、シンプルな Todo リスト管理が可能です。すべてのデータはローカルに保存され、サーバーやアカウントは一切不要です。

### ブラウザ対応状況

| ブラウザ | サポート |
|---|---|
| Microsoft Edge（Chromium ベース） | ✅ 完全対応 |
| Google Chrome | ✅ 完全対応 |

### 機能一覧

| 機能 | 説明 |
|---|---|
| **タブ一覧** | 開いているタブをドメイン別にカードグリッドで表示 |
| **重複検出** | 同ドメイン内の重複タブをハイライトし、ワンクリックで閉じる |
| **グループ閉じ** | ドメイングループのタブをまとめて一括クローズ |
| **後で見る** | タブを右サイドバーのチェックリストに保存し、閉じずにキープ |
| **Todo に追加** | タブのタイトルをチップから直接 Todo に登録 |
| **Todo リスト** | 右パネルで追加・完了・削除が可能、`chrome.storage.local` に永続保存 |
| **挨拶と日付** | 時間帯に応じた挨拶と今日の日付をヘッダーに表示 |
| **重複タブバナー** | Tab Close タブが複数開いた場合に自動検出し、余分なタブを閉じるよう促す |
| **完全ローカル** | 通信なし、アカウント不要、テレメトリなし |

### インストール方法

**Microsoft Edge**

1. このリポジトリをクローンまたはダウンロード
2. Edge で `edge://extensions/` を開く
3. 左下の**開発者モード**を有効化
4. **展開して読み込む**をクリックし、`extension/` フォルダを選択
5. 新しいタブを開くと Tab Close が表示されます

**Google Chrome**

1. このリポジトリをクローンまたはダウンロード
2. Chrome で `chrome://extensions/` を開く
3. 右上の**デベロッパーモード**を有効化
4. **パッケージ化されていない拡張機能を読み込む**をクリックし、`extension/` フォルダを選択
5. 新しいタブを開くと Tab Close が表示されます

### 技術スタック

- バニラ JS（ES2022）+ HTML + CSS
- Chrome 拡張機能 Manifest V3（Edge 互換）
- すべての永続化に `chrome.storage.local` を使用

### クレジット

作者：[Yobot](https://github.com/yobotyao-maker)

### ライセンス

MIT
