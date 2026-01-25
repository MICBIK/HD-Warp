<p align="center">
  <img src="docs/screenshots/banner.png" alt="HD Warp Banner" width="600"/>
</p>

<h1 align="center">🚀 HD Warp - 无感换号网关</h1>

<p align="center">
  <strong>Warp IDE 多账号无感切换工具，无需重启即可自动切换账号</strong>
</p>

<p align="center">
  <a href="#功能特点">功能特点</a> •
  <a href="#下载安装">下载安装</a> •
  <a href="#快速开始">快速开始</a> •
  <a href="#常见问题">常见问题</a> •
  <a href="#联系我们">联系我们</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/平台-macOS%20|%20Windows-blue?style=for-the-badge" alt="Platform"/>
  <img src="https://img.shields.io/badge/版本-v1.1.2-green?style=for-the-badge" alt="Version"/>
  <img src="https://img.shields.io/badge/状态-活跃维护-brightgreen?style=for-the-badge" alt="Status"/>
</p>

---

## ✨ 功能特点

| 功能 | 说明 |
|------|------|
| 🔄 **无感切换** | IDE 无需重启，自动切换账号 |
| 🌐 **代理网关** | 基于 MITM 代理拦截和修改请求 |
| 📊 **实时监控** | 积分使用状态实时显示 |
| 🚀 **自动切号** | 积分用完自动切换下一个账号 |
| ⛔ **封号检测** | 自动检测并跳过被封禁的账号 |
| 🔁 **设备轮换** | 支持手动/自动轮换设备标识 |
| 📝 **日志记录** | 详细的操作和切换日志 |
| 🎨 **现代界面** | Electron 桌面应用，简洁易用 |

<p align="center">
  <img src="docs/screenshots/home.png" alt="主界面" width="700"/>
</p>

---

## 📥 下载安装

### 系统要求

| 平台 | 要求 |
|------|------|
| **macOS** | macOS 10.15+ (Catalina 或更高) |
| **Windows** | Windows 10/11 (64位) |

### 下载链接

前往 [Releases](../../releases) 页面下载最新版本：

- **macOS**: `HD-Warp-Mac-v1.1.2.dmg`
- **Windows**: `HD-Warp-Win-v1.1.2-Setup.exe`

> ⚠️ **macOS 用户**：首次打开如遇"应用已损坏"提示，请在终端执行：
> ```bash
> sudo xattr -rd com.apple.quarantine /Applications/HD\ Warp.app
> ```

---

## 🚀 快速开始

### Step 1️⃣ 安装依赖

**macOS 用户**（打开终端执行）：

```bash
# 安装 Homebrew（如已安装可跳过）
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# 安装 Python 和 mitmproxy
brew install python@3.13 mitmproxy
```

**Windows 用户**：
- 下载安装 [Python 3.10+](https://www.python.org/downloads/)
- 打开 CMD 执行：`pip install mitmproxy`

### Step 2️⃣ 安装证书

1. 启动 HD Warp 应用
2. 进入「网关中心」页面
3. 点击「生成证书」→「立即安装」
4. 按提示将证书设为**始终信任**

### Step 3️⃣ 添加账号

1. 进入「账号池」页面
2. 点击「添加账号」
3. 输入 API Key（每行一个，格式 `wk-xxx`）

> 💡 API Key 获取：Warp → Settings → Account → Create API Key

### Step 4️⃣ 启动网关

1. 进入「网关中心」
2. 输入激活码完成验证
3. 点击「启动网关」
4. 正常使用 Warp 即可 ✅

---

## ❓ 常见问题

<details>
<summary><b>Q: 启动后 Warp 无法使用 AI 功能？</b></summary>
<br/>
请检查证书是否已安装并设为「始终信任」。在「钥匙串访问」中搜索 mitmproxy 可查看证书状态。
</details>

<details>
<summary><b>Q: 遇到 403 Forbidden 错误？</b></summary>
<br/>
403 通常是账号临时受限，请继续尝试发送请求。系统会自动检测并切换到其他可用账号。
</details>

<details>
<summary><b>Q: 初次启动时 AI 请求失败？</b></summary>
<br/>
首次启动需验证所有账号状态，建议等待左下角「就绪账号」数量稳定后再使用。
</details>

<details>
<summary><b>Q: 显示 502 Bad Gateway？</b></summary>
<br/>
通常是网络不稳定导致，尝试重启网关或检查网络环境。系统会自动重试。
</details>

---

## 💰 价格方案

| 类型 | 价格 | 说明 |
|------|------|------|
| 天卡 | ¥1 | 新用户试用推荐 |
| 周卡 | ¥2.5 | 短期使用 |
| 月卡 | ¥7 | 性价比之选 |
| 永久卡 | ¥99 | 一次付费永久使用 |

### 🎁 新用户福利

- 购买**天卡**即送 150 额度账号 x2
- 购买**周卡**即送 150 额度账号 x5

### 📦 Warp 试用号

- 150 额度/个：**¥0.25**
- 50 个起享 **8折** 优惠

---

## 🛡️ 售后保障

- ✅ 账号 2 天内封号且未使用，可包补
- ✅ 单个订单可补 1 次
- ✅ 专业技术支持

---

## 📞 联系我们

<p align="center">
  <a href="#">
    <img src="https://img.shields.io/badge/QQ群-1081614469-blue?style=for-the-badge&logo=tencentqq" alt="QQ群"/>
  </a>
</p>

**加入 QQ 群获取**：
- 💡 使用指导和技术支持
- 🔑 激活码购买
- 📦 账号购买
- 📢 最新版本更新通知

---

## 📜 更新日志

### v1.1.2 (2026-01)
- ✨ 优化账号切换逻辑
- 🐛 修复网络恢复问题
- 🎨 界面优化

### v1.1.1
- ✨ 新增设备标识轮换
- 🔧 Rules 动态注入功能
- 📊 统计面板优化

### v1.0.0
- 🎉 首次公开发布

---

<p align="center">
  <sub>Made with ❤️ by HaiDen</sub>
</p>
