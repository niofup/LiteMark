# LiteMark Privacy Policy / 隐私政策

**Publisher / 发布者：** Edward CCAO  
**Product / 产品：** LiteMark  
**Last updated / 最近更新：** 2026-09-14

---

## English

### 1. Summary

LiteMark is a **local Markdown editor**. We do **not** operate a cloud service for your documents. Your notes are opened and saved on your device through the system file picker. We do **not** sell personal data.

### 2. Who we are

- **Controller / Publisher:** Edward CCAO  
- **Product:** LiteMark (desktop application, distributed via Microsoft Store)

### 3. What we collect

| Category | Collected? | Details |
|----------|------------|---------|
| Account / registration | **No** | No sign-up, no email collection in-app |
| Document content | **Not by us** | LiteMark only reads/writes files **you** open or save. Content is not uploaded to the publisher. |
| Analytics / crash telemetry | **No** | No analytics SDK, no crash reporting service |
| Advertising identifiers | **No** | No ads in the app |
| Payment data | **No (publisher)** | Paid purchase and trial are processed by **Microsoft Store**. Card and billing data go to Microsoft, not to us. See [Microsoft’s privacy statements](https://privacy.microsoft.com/). |
| Device identifiers sent to us | **No** | We do not run an account or license server that receives hardware IDs |

### 4. Data stored on your device

LiteMark may store the following **locally only**:

- **UI preferences** (theme, sidebar, fonts, editor mode, etc.) in local application storage (e.g. browser/localStorage-backed settings inside the app).
- **Application data folder** under the OS app-data directory for the app identity `com.litemark.editor` (on Windows, typically `%APPDATA%\com.litemark.editor\`), including:
  - **History / auto-snapshots** of documents you edit (so you can restore earlier versions);
  - logs or similar diagnostic files **on your machine only** (if any).
- **Recently opened file paths** (names/paths of files you opened), used only to show a local “recent” list.

You can clear snapshots and app data by deleting that folder or uninstalling the app (uninstall may leave app-data leftovers depending on Windows behavior; you can delete the folder manually).

### 5. Network activity

LiteMark is designed to work offline for editing. Limited network use can still occur:

1. **Content you reference**  
   If a Markdown document contains `http(s)` image URLs, the embedded web view may request those URLs from third-party servers. Those servers may see your IP address and standard request metadata. LiteMark does not proxy or log those requests. Private-network image URLs (e.g. LAN/localhost) are intentionally not supported for safety.

2. **Microsoft Store / OS components**  
   Installation, updates, licensing, and WebView2 runtime updates are handled by Windows / Microsoft Store under Microsoft’s policies.

3. **Opening external links**  
   If you open a link in the system browser, that navigation is handled by the browser and the destination site.

### 6. Microsoft Store and purchases

- Distribution, payment, refund, and trial entitlement are provided by **Microsoft Store**.
- Microsoft may process personal data for Store accounts and purchases under [Microsoft Privacy Statement](https://privacy.microsoft.com/).
- The publisher does not receive your payment card details from Microsoft for Store purchases.

### 7. Children’s privacy

LiteMark is a general-purpose productivity tool and is **not directed at children under 13** (or the minimum age in your region). We do not knowingly collect personal information from children.

### 8. Your choices

- Do not open documents or remote images if you do not want related local or third-party access.
- Uninstall the app to stop all use; delete the app-data folder to remove local snapshots/settings.
- For Store purchase issues, use Microsoft Store account and support channels.

### 9. Changes to this policy

We may update this policy when features change. The “Last updated” date at the top will change. Material changes will be reflected here before or when a Store update ships, as applicable.

### 10. Contact

For privacy questions about LiteMark:

- **Publisher:** Edward CCAO  
- **Contact email:** edwardqccao@outlook.com

### 11. Scope

This policy applies to the **LiteMark** desktop application distributed as **LiteMark** by Edward CCAO, including Store builds.

---

## 中文

### 1. 概要

LiteMark 是一款**本地 Markdown 编辑器**。我们**不**为你的文档提供云端同步服务。文档由你通过系统对话框在本机打开与保存。我们**不出售**个人数据。

### 2. 我们是谁

- **发布者 / 责任主体：** Edward CCAO  
- **产品：** LiteMark（桌面应用，经 Microsoft Store 分发）

### 3. 我们收集什么

| 类别 | 是否收集 | 说明 |
|------|----------|------|
| 账号 / 注册 | **否** | 应用内无注册、不收集邮箱 |
| 文档正文 | **我们不收集** | LiteMark 仅读写**你**打开或保存的本地文件，正文不上传至发布者 |
| 分析 / 崩溃遥测 | **否** | 无分析 SDK、无崩溃上报服务 |
| 广告标识 | **否** | 应用内无广告 |
| 支付数据 | **（发布者）否** | 买断与试用由 **Microsoft Store** 处理；账单与支付信息归微软，不进入发布者服务器。参见 [Microsoft 隐私声明](https://privacy.microsoft.com/zh-cn/) |
| 发送给我们的设备标识 | **否** | 我们不运营会接收硬件 ID 的账号或许可服务器 |

### 4. 仅存在你设备上的数据

LiteMark 可能**仅在本地**保存：

- **界面偏好**（主题、侧栏、字体、编辑器模式等），存放于应用本地设置（如 localStorage 一类的应用内存储）。
- **应用数据目录**（应用标识 `com.litemark.editor`；Windows 上通常为 `%APPDATA%\com.litemark.editor\`），可能包含：
  - **历史 / 自动快照**（便于恢复此前版本）；
  - 仅存本机的诊断日志（若有）。
- **最近打开的文件路径**，仅用于本地「最近」列表。

可通过删除上述目录或卸载应用清除（卸载后 Windows 上应用数据可能仍残留，可手动删除该目录）。

### 5. 网络行为

编辑功能以离线为主。仍可能发生的有限联网包括：

1. **你文档中引用的内容**  
   若 Markdown 中含有 `http(s)` 图片地址，内置 WebView 可能向第三方服务器请求这些资源。对方可能看到你的 IP 与常规请求信息。LiteMark 不代理、不记录这些请求。出于安全考虑，**不支持**内网 / localhost 等私网图片地址。

2. **Microsoft Store / 系统组件**  
   安装、更新、许可及 WebView2 运行时更新由 Windows / Microsoft Store 按微软政策处理。

3. **打开外部链接**  
   你在系统浏览器中打开的链接由浏览器与目标网站处理。

### 6. Microsoft Store 与购买

- 分发、付款、退款与试用资格由 **Microsoft Store** 提供。
- 微软可能依据 [Microsoft 隐私声明](https://privacy.microsoft.com/zh-cn/) 处理 Store 账号与购买相关个人数据。
- Store 购买的支付卡信息不会由微软提供给发布者。

### 7. 儿童隐私

LiteMark 面向通用生产力场景，**不面向 13 周岁以下**（或你所在地区法定最低年龄）儿童。我们不会故意收集儿童个人信息。

### 8. 你的选择

- 不希望产生本地读取或第三方图片请求时，请不要打开相应文档或外链图片。
- 卸载应用可停止使用；删除应用数据目录可清除本地快照与设置。
- 购买与退款问题请通过 Microsoft Store 账号与微软支持渠道处理。

### 9. 政策变更

功能变化时我们可能更新本政策，并修改文首「最近更新」日期。如有重大变更，将在 Store 更新上线前或同步在此说明（视情况而定）。

### 10. 联系方式

有关 LiteMark 的隐私问题：

- **发布者：** Edward CCAO  
- **联系邮箱：** edwardqccao@outlook.com

### 11. 适用范围

本政策适用于由 Edward CCAO 以 **LiteMark** 名义分发的 **LiteMark** 桌面应用，包括 Store 构建版本。
