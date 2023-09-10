<p align="center"><img src="./app/assets/images/SealCircle.png" width="150px" height="150px" alt="aventium softworks"></p>

<h1 align="center">BDSTW Launcher</h1>

<em><h5 align="center">(formerly Electron Launcher)</h5></em>

[<p align="center"><img src="https://img.shields.io/github/actions/workflow/status/dscalzi/HeliosLauncher/build.yml?branch=master&style=for-the-badge" alt="gh actions">](https://github.com/dscalzi/HeliosLauncher/actions) [<img src="https://img.shields.io/github/downloads/dscalzi/HeliosLauncher/total.svg?style=for-the-badge" alt="downloads">](https://github.com/dscalzi/HeliosLauncher/releases) <img src="https://forthebadge.com/images/badges/winter-is-coming.svg"  height="28px" alt="winter-is-coming"></p>

<p align="center">加入模組伺服器，無需擔心安裝 Java、Forge 或其他模組 我們會為您處理的。</p>

![Screenshot 1](https://i.imgur.com/6o7SmH6.png)
![Screenshot 2](https://i.imgur.com/x3B34n1.png)

## Features

* 🔒 完整的帳戶管理。
  * 添加多個帳戶並輕鬆切換。
  * 完全支持 Microsoft（OAuth 2.0）+ Mojang（Yggdrasil）身份驗證。
  * 憑據永遠不會直接存儲和傳輸到 Mojang。
* 📂 高效的資源管理。
  * 我們發布更新後，您將立即收到客戶端更新。
  * 在啟動之前驗證文件。損壞或錯誤的文件將重新下載。
* ☕ **自動 Java 驗證。**
  * 如果您安裝了不兼容版本的 Java，我們將為您安裝正確版本的 Java。
  * 您無需安裝 Java 即可運行啟動器。
* 📰 登入器內置公告提要功能
* ⚙️ 直觀的設置管理，包括Java控制面板
* 支持所有我們的伺服器
   * 輕鬆切换登入器配置
   * 查看所選登入器上玩家数量
* 自動更新。没錯，啟動器會自己更新.
* 查看Mojang服务状态。

這並非詳盡無遺之列。下載並安裝啟動器以體驗其全部功能！

#### 需要幫助嗎？[查看維基。][wiki]
#### 喜歡這個項目嗎？在repository上留下⭐星！
## 下載

You can download from [GitHub Releases](https://github.com/Stevebell-sp/BDSTWLauncher/releases)

**Supported Platforms**

| Platform | File |
| -------- | ---- |
| Windows x64 | `Helios-Launcher-setup-VERSION.exe` |
| macOS x64 | `Helios-Launcher-setup-VERSION-x64.dmg` |
| macOS arm64 | `Helios-Launcher-setup-VERSION-arm64.dmg` |
| Linux x64 | `Helios-Launcher-setup-VERSION.AppImage` |

## Console

To open the console, use the following keybind.

```console
ctrl + shift + i
```

Ensure that you have the console tab selected. Do not paste anything into the console unless you are 100% sure of what it will do. Pasting the wrong thing can expose sensitive information.

#### Export Output to a File

If you want to export the console output, simply right click anywhere on the console and click **Save as..**

![console example](https://i.imgur.com/T5e73jP.png)


## Development

This section details the setup of a basic developmentment environment.

### Getting Started

**System Requirements**

* [Node.js][nodejs] v18

---

**Clone and Install Dependencies**

```console
> git clone https://github.com/dscalzi/HeliosLauncher.git
> cd HeliosLauncher
> npm install
```

---

**Launch Application**

```console
> npm start
```

---

**Build Installers**

To build for your current platform.

```console
> npm run dist
```

Build for a specific platform.

| Platform    | Command              |
| ----------- | -------------------- |
| Windows x64 | `npm run dist:win`   |
| macOS       | `npm run dist:mac`   |
| Linux x64   | `npm run dist:linux` |

Builds for macOS may not work on Windows/Linux and vice-versa.