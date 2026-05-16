---
title: 隐私政策 · Privacy Policy
permalink: /privacy/
---

# MangaRoll · 漫画时光卷 隐私政策

**生效日期: 2026 年 5 月 6 日**
**最近更新: 2026 年 5 月 16 日**

我们尊重并致力于保护使用 MangaRoll · 漫画时光卷(以下简称"本应用")的所有用户的个人信息及隐私权。本隐私政策将帮助你了解我们收集哪些信息、如何使用这些信息、以及你享有的权利。在使用本应用前,请仔细阅读并理解本政策。

本应用同时提供 iOS App 和微信小程序两种形式,本政策同时适用于二者。如果你对本政策有任何疑问,可通过本文末「联系我们」中提供的方式与我们联系。

---

## 一、我们收集的信息

### 1.1 你直接提供的信息

- **照片**: 当你使用「生成漫画」功能时,你需要从相册选择 1–3 张照片。这些照片将上传至我方服务器及第三方 AI 服务用于生成漫画图像。
- **昵称与头像**: 在你完成登录后,我们会保存你的昵称和头像,用于在社区(灵感广场、评论、好友共创)中展示。你可以随时修改。
- **作品配文**: 你为生成的漫画作品所写的配文、评论、举报理由等文字内容。
- **意见反馈**: 你通过应用内反馈渠道(如有)向我们提交的内容。

### 1.2 我们自动收集的信息

- **账号标识符**: 通过 Apple Sign In 登录时,Apple 提供给我们的不可逆匿名 ID(`sub`);通过微信登录时,微信开放平台提供的 `openid` 与 `unionid`(用于跨设备/跨平台数据互通)。
- **设备信息**: 设备型号、操作系统版本、应用版本、语言与时区,用于功能适配与故障排查。
- **使用日志**: 你在应用内的关键操作时间戳(如生成、发布、点赞)、网络请求日志,用于诊断问题与优化体验。
- **崩溃与性能数据**: 应用崩溃堆栈、关键页面加载耗时,通过 Apple 提供的 TestFlight / Xcode Cloud 与本应用自有日志收集。

### 1.3 购买相关信息

当你购买钻石或会员时,**Apple 公司**(iOS)或**微信支付**(微信小程序)处理实际支付,我们仅接收交易凭证以记录订单状态(订单号、商品 ID、购买时间),**不会**接触你的银行卡号、CVV 或其他支付凭据。

### 1.4 我们**不**收集的信息

- 精确地理位置(GPS)
- 通讯录、短信、通话记录
- 健康与健身数据
- 浏览器历史、搜索历史
- 麦克风音频、摄像头实时画面(仅访问相册中的静态照片)
- IDFA(广告标识符) — 我们不进行跨应用广告追踪

---

## 二、我们如何使用这些信息

我们仅出于以下目的使用上述信息:

1. **核心功能**: 生成漫画、发布作品、社区互动、好友共创、订单与会员管理
2. **账号体系**: 用户身份识别、跨平台数据同步(iOS ↔ 微信小程序通过 unionid)
3. **内容安全**: 对你上传的照片与发布的文字内容进行 AI 内容审核(参见第四节)
4. **客户服务**: 回应你的问题与申诉
5. **安全与防滥用**: 检测与防御异常账号、刷量、恶意行为
6. **故障排查与产品改进**: 通过崩溃日志、性能数据分析问题
7. **遵守法律义务**: 配合中国大陆与适用司法辖区的法律、法规、行政与司法机关的合法要求

我们**不会**:

- 将你的个人信息用于跨应用广告投放或行为画像
- 出售或出租你的个人信息
- 在未获得你明确同意的情况下用于本政策所列以外的用途

---

## 三、我们如何共享信息

我们仅在以下情形与第三方共享信息,并要求该等第三方履行不低于本政策的保密与安全义务:

### 3.1 必要的第三方服务提供商

| 第三方 | 数据类型 | 用途 | 留存期 |
|---|---|---|---|
| **Apple Inc.**(美国) | Apple ID 匿名标识符 (`sub`)、IAP 订单元数据 | iOS 登录、内购校验、推送通知 | 由 Apple 隐私政策约束 |
| **腾讯云 CloudBase**(中国大陆,上海/广州区域) | 全部业务数据(用户、作品、订单、聊天) | 后端数据库与文件存储 | 至账号注销后 30 天 |
| **腾讯云内容安全**(中国大陆) | 上传图片、用户提交的文本 | 自动审核色情、暴力、政治敏感等违规内容 | 审核日志保留 6 个月 |
| **Google LLC — Gemini API**(美国,经代理 Poixe / API易) | 你上传的照片(临时传输) | 分析照片内容用于叙事结构(故事类型、主图判断、情绪标签) | **不留存,本次请求结束即丢弃**;Google 承诺 Gemini API 数据不用于训练模型 |
| **字节跳动 — 即梦 (Seedream)**(中国大陆) | 你上传的照片(临时传输) + 文本提示词 | 生成漫画图像 | **不留存,本次请求结束即丢弃**;字节跳动承诺 API 输入不用于训练模型 |
| **字节跳动 — 豆包 (Doubao)**(中国大陆) | 文本提示词(派生自照片分析结果,**不**包含照片) | 生成漫画配文 | **不留存,本次请求结束即丢弃** |
| **腾讯混元 (Hunyuan)**(中国大陆) | 文本提示词 | 部分场景下的文案与审核辅助 | **不留存,本次请求结束即丢弃** |
| **微信开放平台**(中国大陆) | openid / unionid | 微信登录与跨平台账号关联(仅当你选择微信登录时) | 由微信隐私政策约束 |

### 3.1.1 我们对上述第三方的合规要求

我们已与上述每一家第三方签署或确认以下事项,确保它们提供**不低于本政策的保护水平**:

1. **数据最小化**:每次请求只发送当次生成所必需的最少数据(选中的 1-9 张照片 + 派生的文字提示)
2. **传输加密**:所有出站请求均通过 HTTPS / TLS 1.2+
3. **不用于训练**:Google Gemini API、字节跳动开放平台、腾讯云均在其官方 API 服务条款中承诺 API 输入不用于其大模型训练
4. **不二次分享**:第三方收到的数据不会被转售给广告商、数据经纪商或其他用途
5. **审计与撤回**:你可随时通过 App「设置 → AI 服务发送同意」关闭后续生成调用,或通过本文末邮箱要求我们提供数据访问/删除报告

### 3.1.2 关于"AI 是否会处理人脸"

我们的 App **不**做任何"人脸识别 / 人脸特征提取 / 人脸库构建":
- 我们**不使用** Apple Vision、CIDetector 等任何本地人脸识别 API
- 我们**不使用** Apple FaceID 或任何生物特征识别
- 我们**不会**将照片中的人脸数据存入数据库,**不会**为任何人建立人脸索引
- 上述第三方 AI 服务**仅**将照片作为整体视觉输入用于图像风格化生成,生成完成后立即丢弃,**不**保留人脸特征向量

如果你上传的照片中包含人脸(本人或他人),它将与照片中其他视觉元素(背景、物体、构图)一并被风格化为漫画。我们**强烈建议**在上传他人照片前征得其同意。

### 3.2 法律与安全

在必要时,我们可能向公安、司法机关或其他依法享有调查权的政府部门披露信息,包括但不限于配合刑事侦查、保护本应用与用户的合法权益。

### 3.3 业务转让

如本应用涉及合并、收购或资产转让,你的信息可能作为被转让资产的一部分。在此情形下我们将以显著方式通知你,并确保受让方继续遵守不低于本政策的标准。

---

## 四、内容审核

为遵守《网络安全法》《互联网信息服务管理办法》《App 信息内容生态治理规定》等中国大陆法律法规,以及 Apple App Store 审核规则,我们使用**腾讯云内容安全**对以下内容进行**自动审核**:

- 你上传的照片(在被发送至 AI 生成服务**之前**)
- 你发布的作品配文、评论、昵称、举报理由等文字
- 头像图片

涉嫌违规的内容将被自动拦截。审核结果可能保存日志用于争议处理、监管检查与产品改进。我们**不会**对私人对话(如私信,如未来上线)进行实时人工查阅,但保留对涉嫌违法内容进行核查与配合调查的权利。

---

## 五、数据保留

| 数据类型 | 保留期 |
|---|---|
| 你上传的照片(原图) | 生成完成后 **30 天**自动删除 |
| AI 生成的漫画图像 | 你主动删除前永久保留;账号注销后 30 天内删除 |
| 已发布作品 | 你主动删除或注销账号前永久保留 |
| 账号信息 | 直至你注销账号 |
| 订单记录 | 依据中国大陆《电子商务法》《税收征收管理法》保留 **不少于 3 年** |
| 内容审核日志 | 依据《网络安全法》保留 **不少于 6 个月** |
| 崩溃与性能日志 | **90 天** |

注销账号后 30 天内,除上述法律要求保留的数据外,所有可识别个人身份的信息将被永久删除。

---

## 六、数据安全

我们采取以下措施保护你的信息:

- 全链路 **HTTPS / TLS 1.3** 加密传输
- 服务器端数据加密存储
- JWT 签名认证 + Apple Keychain 本地凭据存储
- 严格的角色权限控制,仅有限工程师可访问生产数据
- 定期安全扫描与漏洞修复

尽管我们尽力保护,但请你理解:互联网传输不存在绝对安全。请妥善保管你的设备、Apple ID 与微信账号。

---

## 七、你的权利

依据中国大陆《个人信息保护法》、欧盟《一般数据保护条例》(GDPR)、加州《消费者隐私法》(CCPA)等适用法律,你享有以下权利:

- **查阅、复制权**: 可在「我的」页面查看所有你的作品、订单、订阅状态
- **更正权**: 在「我的」页面修改昵称、头像
- **删除权**: 删除单条作品 → 作品详情页菜单;**永久注销账号** → 设置 → 注销账号(双重确认)
- **拒绝与限制权**: 可在「设置」中关闭推送通知;可拉黑特定用户停止接收其内容
- **数据可携权**: 通过本文末邮箱联系我们,我们将在 30 日内向你提供个人数据导出
- **撤回同意权**: 你可随时撤回此前对个人信息处理的同意,但不影响撤回前已进行的处理
- **投诉权**: 你有权向有管辖权的个人信息保护监管机构投诉

如需行使上述权利,请通过邮箱联系我们。我们将在 **15 个工作日**内回复。

---

## 八、儿童隐私

本应用不面向 **14 周岁以下儿童**提供服务。我们不会有意收集 14 周岁以下儿童的个人信息。如你是儿童的监护人,发现你的被监护人未经你同意使用本应用,请联系我们以删除相关账号与数据。

依据中国大陆《未成年人保护法》《未成年人网络保护条例》,我们对 14 周岁以上未成年人的内购金额设置上限,并提供监护人申诉退款渠道。

---

## 九、跨境数据传输

主要存储位于**中国大陆**(腾讯云上海/广州区域)。出于以下目的,部分数据会被传输至中国大陆境外:

- **照片内容分析**: 你上传的照片会经由我方服务器转发至 **Google Gemini API**(美国)。Google 根据其[隐私政策](https://policies.google.com/privacy)处理该数据,**不会**将其用于训练 AI 模型。
- **漫画图像与文案生成**: 派生的文字提示与(部分情形下)照片会发送至**字节跳动 即梦 / 豆包**与**腾讯混元**(中国大陆境内 — 不构成跨境传输,但我们在此一并披露以保持透明)。
- **iOS 推送通知**: 通过 **Apple Push Notification Service**(美国)。

我们会在合理范围内确保该等跨境传输符合所适用的数据保护法律。

---

## 十、政策变更

我们可能不时更新本政策。重大变更将在应用启动页或以推送通知方式提示你,并在文首更新「最近更新」日期。继续使用本应用即表示你接受更新后的政策。

---

## 十一、联系我们

| 渠道 | 信息 |
|---|---|
| 应用名称 | MangaRoll · 漫画时光卷 |
| Bundle ID | com.mangaroll.app |
| 邮箱 | zooms@annauniv.edu |
| 应答时长 | 一般情况下 **5 个工作日**内回复 |

---

# Privacy Policy (English Summary)

**Effective: May 6, 2026**

This is a brief English summary. The Chinese version above is authoritative.

**What we collect:**
- Photos you upload (1–3 per generation)
- Apple ID anonymous identifier or WeChat openid/unionid
- Nickname, avatar, captions, comments
- Device info, crash logs, performance data
- IAP order metadata (no card data — Apple/WeChat Pay handle that)

**What we do NOT collect:** precise location, contacts, microphone, IDFA, browsing history.

**Who we share with:** Apple (login + IAP, USA), Tencent CloudBase (backend, China), Tencent Cloud Content Moderation (compliance, China), Google Gemini (photo content analysis, USA — photos NOT used for training), ByteDance Seedream + Doubao (image/text generation, China — inputs NOT used for training), Tencent Hunyuan (auxiliary text generation, China), WeChat Open Platform (WeChat login only).

**Face data:** This app does NOT perform face detection, face recognition, or face feature extraction. We do NOT use Apple Vision, CIDetector, FaceID, or any other biometric API. Photos may contain faces (yours or others') but those faces are processed by the AI services only as part of the overall image for stylization, not for biometric identification. No face database is built. No face features are stored.

**Retention:** uploaded photos auto-deleted after 30 days; account data until you delete; order records ≥ 3 years (China e-commerce law); moderation logs ≥ 6 months (China Cybersecurity Law).

**Your rights:** access, correct, delete, export, withdraw consent, complain to regulators. Account deletion is in-app: Settings → Delete Account (double confirmation).

**Children:** not for users under 14.

**Cross-border:** photos transit to Google Gemini (USA) for generation; Apple push (USA). Primary storage in mainland China.

**Contact:** zooms@annauniv.edu

---

© 2026 MangaRoll · 漫画时光卷
