<div align="center">

# 留白写作 · 桌面版

**专业的 AI 写作软件**　·　Mac / Windows / Linux 客户端

功能与网页版 [liubaiai.com](https://liubaiai.com) 完全一致，作品数据本地保存。

### 👉 [点此前往最新版下载](../../releases/latest)

</div>

---

## ⬇️ 选择你的系统

在下载页底部的 **Assets（资源）** 里，按系统下载对应文件：

| 你的系统 | 下载这个文件 | 备注 |
|---|---|---|
| 🍎 **macOS（Apple 芯片 M1/M2/M3/M4）** | `留白写作_x.x.x_aarch64.dmg` | 目前仅支持 Apple 芯片 |
| 🪟 **Windows 10/11（64 位）** | `留白写作_x.x.x_x64-setup.exe` | 双击安装 |
| 🐧 **Linux（Ubuntu/Debian）** | `留白写作_x.x.x_amd64.deb` | 命令行安装 |
| 🐧 **Linux（通用）** | `留白写作_x.x.x_amd64.AppImage` | 免安装，赋权即用 |

> 💡 **怎么看 Mac 是不是 Apple 芯片？** 屏幕左上角  → **关于本机** → 看「芯片」一栏：写 **Apple** 就下 `aarch64.dmg`；写 **Intel** 的暂不支持，请先用网页版。

---

## 📦 安装步骤

<details open>
<summary><b>🍎 macOS</b></summary>

1. 双击下载好的 `.dmg`
2. 把「**留白写作**」图标**拖进「应用程序」**文件夹
3. 到「应用程序」里打开它

</details>

<details>
<summary><b>🪟 Windows</b></summary>

1. 双击 `留白写作_x.x.x_x64-setup.exe`
2. 按提示完成安装
3. 从「开始菜单」打开「留白写作」

</details>

<details>
<summary><b>🐧 Linux</b></summary>

- **.deb（Ubuntu/Debian）**：
  ```bash
  sudo dpkg -i 留白写作_*.deb
  ```
- **.AppImage（通用）**：
  ```bash
  chmod +x 留白写作_*.AppImage
  ./留白写作_*.AppImage
  ```

</details>

---

## 🛠 打开时遇到问题？（重要）

> 目前安装包**暂未做系统签名**，所以首次打开时 Mac / Windows 可能会拦一下。**这不是病毒，也不是文件损坏**，按下面操作即可正常使用。

<details open>
<summary><b>🍎 Mac 提示「"留白写作.app"已损坏，无法打开，应该移到废纸篓」</b></summary>

**先点「取消」，不要移到废纸篓！** 它没坏，是 macOS 的拦截。二选一解决：

**方法一（推荐）**：打开「**终端**」（按 `⌘ + 空格`，输入「终端」回车），粘贴这行回车：
```bash
xattr -cr /Applications/留白写作.app
```
然后回「应用程序」正常双击打开即可。

**方法二**：在「应用程序」里**右键点**「留白写作」→ 选「**打开**」→ 在弹窗里再点「**打开**」。

</details>

<details>
<summary><b>🪟 Windows 提示「Windows 已保护你的电脑」（SmartScreen）</b></summary>

在蓝色提示框里点 **「更多信息」** → 再点 **「仍要运行」** 即可。

</details>

<details>
<summary><b>下载很慢 / 打不开下载页？</b></summary>

- 刷新重试，或换个网络环境。
- 仍不行，可联系官方或在 [Issues](../../issues) 反馈。

</details>

---

## ℹ️ 关于

- 桌面版与网页版 **[liubaiai.com](https://liubaiai.com)** 功能一致，账号、会员、字数包通用。
- 作品主数据保存在你的本地电脑。
- 登录、订阅等仍通过官方服务器。

---

<div align="center">
<sub>留白写作团队　·　遇到问题欢迎在 <a href="../../issues">Issues</a> 反馈</sub>
</div>
