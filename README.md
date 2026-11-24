<div align="center">

# Hi, I'm Kianuni 👋

**Native Swift tools for iOS, iPadOS & macOS**  
System Customization · Apple Intelligence Routing & Diagnostics · Sideload Security · Offline Privacy

专注 **iOS / iPadOS / macOS 原生 Swift 工具** —— 覆盖系统配置、零适应成本离线输入法、Apple 智能零 MitM 分流与排障、锁屏美学、侧载安全审计与硬件级离线隐私。

<p>
  <a href="https://trendshift.io/repositories/347713" target="_blank">
    <img src="https://trendshift.io/api/badge/trendshift/repositories/347713/weekly?language=Swift" alt="Trendshift #2 Swift Repository Of The Week" width="230" height="51">
  </a>
</p>

</div>

---

### ⭐ Featured Spotlight / 重点推荐：`Lokey · 落键`

> **1:1 iOS 26 原生手感（零学习适应成本）· 物理级零联网（0 网络框架 / 源码可审计）· 落墨离线引擎 · 55 万词白霜扩展热挂载**  
> Native iOS 26 ergonomics with zero learning curve, physically zero-network Chinese Pinyin/Shuangpin keyboard (`otool`/`nm` auditable) & read-only `mmap` external lexicons.
>
> 🌐 **[Lokey 产品官网 (Showcase)](https://kianuni.github.io/Lokey-Audit/)** · 🔒 **[零联网审计仓 (Lokey-Audit)](https://github.com/Kianuni/Lokey-Audit)** · 📦 **[55 万词白霜扩展包 (lokey-frost-pack)](https://github.com/Kianuni/lokey-frost-pack)**

---

### 🧰 Apple Ecosystem Toolkit / 开源项目矩阵

> 所有主力项目均坚持 **原生 Swift · 零第三方追踪 · 中英双语 · 安全边界优先**。

| Project | Category / 定位 | What It Does / 核心能力 | Stats |
| :--- | :--- | :--- | :---: |
| **[Erosion-CN](https://github.com/Kianuni/Erosion-CN)** | 系统配置 · `MobileGestalt` | Bootloop-safe iOS/iPadOS MobileGestalt toolbox with in-place writes, runtime slot resolution & dual SHA-256 backups.<br>防白苹果安全加固版系统配置工具箱（原位写入、零硬编码偏移、双重原厂备份）。 | ![Stars](https://img.shields.io/github/stars/Kianuni/Erosion-CN?style=flat-square&color=F59E0B&label=) |
| **[Lokey · 落键](https://kianuni.github.io/Lokey-Audit/)** | 原生手感 · 离线输入法 | 1:1 iOS 26 Liquid Glass ergonomics (zero learning curve), physically zero-network Full Pinyin & Xiaohe/Ziranma Shuangpin keyboard ([`Lokey-Audit`](https://github.com/Kianuni/Lokey-Audit) · [`lokey-frost-pack`](https://github.com/Kianuni/lokey-frost-pack)).<br>1:1 原生手感零学习成本、0 网络框架/可独立 Mach-O 审计的离线中文输入法，支持 55.3 万词白霜 `.lokeypack` 只读 `mmap` 热挂载。 | ![Audit Stars](https://img.shields.io/github/stars/Kianuni/Lokey-Audit?style=flat-square&color=F59E0B&label=) |
| **[AppleFlow](https://github.com/Kianuni/AppleFlow)** | 网络分流 · Apple 智能 | Zero-MitM routing rulesets & local config doctor for Apple Intelligence, PCC Photos Clean Up & Chinese Siri ([Web Workbench](https://kianuni.github.io/AppleFlow/)).<br>零 MitM 的 Apple 智能 / 相册消除 / 中文 Siri 极简分流与在线体检台。 | ![Stars](https://img.shields.io/github/stars/Kianuni/AppleFlow?style=flat-square&color=F59E0B&label=) |
| **[AppleLens](https://github.com/Kianuni/AppleLens)** | macOS 观测 · 真机排障 | Zero-MitM, read-only macOS MenuBar & Workbench for USB iPhone logs, routing probes & PCC transparency reports.<br>纯只读 macOS 菜单栏与工作台，一键排查 Apple 智能与 Siri 真机日志。 | ![Stars](https://img.shields.io/github/stars/Kianuni/AppleLens?style=flat-square&color=F59E0B&label=) |
| **[Camlo](https://github.com/Kianuni/Camlo)** | 锁屏美学 · 动态壁纸 | 1-tap dynamic, slide-to-unlock morph & 3D depth Lock Screen wallpapers with 76 curated themes (iOS & iPhone Duo).<br>免电脑一键直写上滑变身、裸眼 3D 与动态锁屏，内置 76 套大师壁纸图鉴。 | ![Stars](https://img.shields.io/github/stars/Kianuni/Camlo?style=flat-square&color=F59E0B&label=) |
| **[WQGuard](https://github.com/Kianuni/WQGuard)** | 侧载安全 · CVE 防护 | 100% read-only Swift IPA static Mach-O/CSBlob auditor, sandbox escape detector & 5-client Brotli CVE shields.<br>零依赖只读侧载 IPA 验毒审计引擎 + 五大代理端防 `CVE-2026-111497` 护盾。 | ![Stars](https://img.shields.io/github/stars/Kianuni/WQGuard?style=flat-square&color=F59E0B&label=) |
| **[Enkard](https://github.com/Kianuni/Enkard)** | 离线隐私 · 安全芯片 | Pure offline, zero-network iPhone financial card vault hardware-bound to Apple Secure Enclave.<br>零联网代码、零云端同步、绑定 Apple Secure Enclave 安全芯片的私人卡包。 | ![Stars](https://img.shields.io/github/stars/Kianuni/Enkard?style=flat-square&color=F59E0B&label=) |

---

### 🔗 Recommended Workflows / 推荐搭配使用

- **国行 / 外版满血 Apple 智能三件套**：`Erosion-CN`（底层配置） → `AppleFlow`（零 MitM 分流与体检） → `AppleLens`（macOS 真机日志诊断）
- **零联网日常输入与隐私双件套**：**[Lokey · 落键](https://kianuni.github.io/Lokey-Audit/)**（原生手感物理零联网输入法） + **[lokey-frost-pack](https://github.com/Kianuni/lokey-frost-pack)**（55.3 万词白霜扩展包） + **[Enkard](https://github.com/Kianuni/Enkard)**（Secure Enclave 离线卡包）
- **安全侧载与日常进阶**：安装第三方 `.ipa` 前先用 `WQGuard` 静态验毒 → 搭配 `Camlo` 定制动态锁屏 → 用 `Erosion-CN` APFS 暂存舱安全换签

---

### 🛡️ Engineering Principles / 工程原则

- **Pure Native Swift**：优先采用原生 Darwin / POSIX / SwiftUI，尽量零第三方 SDK 依赖。
- **Safety First**：涉及底层读写的工具坚持原位校验、只读隔离（`O_RDONLY | O_NOFOLLOW`）与完整回滚机制。
- **Bilingual by Default**：全系列主力项目均原生支持简体中文与英文。
