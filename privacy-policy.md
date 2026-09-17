# BiuEcho 隐私权政策 / Privacy Policy

> 生效日期 / Effective date：2026-09-18  
> 产品 / Product：BiuEcho（Chrome 扩展 · 多平台 AI 对话可见度监测）  
> 运营方联系邮箱 / Contact： [service@3biu.cn](mailto:service@3biu.cn)  
> 建议公网地址 / Suggested public URL：`https://geo.3biu.cn/privacy`  
> 配套可部署页面：同目录 [`privacy-policy.html`](./privacy-policy.html)

本文供 Chrome 网上应用店「隐私权政策」字段使用。部署 `privacy-policy.html`（或等价 Markdown 渲染页）到公网 HTTPS 后，将 URL 填入 Developer Dashboard。

---

## 中文

### 1. 概述

BiuEcho（下称「本扩展」或「本服务」）用于在用户选定的 AI 对话网页上，按用户配置自动投放提示词，采集回复内容与截图，并可选进行关键词匹配，以评估品牌或关键词在 AI 回答中的可见度。

本政策说明我们如何收集、使用、存储、共享与保护相关用户数据。使用本扩展即表示您知悉本政策所述做法。若您不同意，请停止使用并卸载本扩展。

### 2. 运营方与联系方式

- 产品名称：BiuEcho  
- 数据服务域名（默认）：`https://geo.3biu.cn`  
- 联系邮箱：service@3biu.cn  

如需查阅、更正、导出或删除与您账号相关的云端数据，或对本政策有疑问，请通过上述邮箱联系我们。

### 3. 我们收集哪些数据

根据您使用免费版或付费版，以及您开启的检测选项，本扩展可能处理下列数据：

#### 3.1 个人身份信息

- 付费账号登录时使用的**电子邮件地址**
- 账号相关的客户/套餐标识（用于授权范围）

#### 3.2 身份验证信息

- 邮箱登录时提交的**密码**（用于鉴权；传输使用 HTTPS；我们不会在商店页面或扩展界面中公开展示密码）
- 访问**令牌 / 凭证**（用于维持登录会话）

#### 3.3 网站内容与用户生成内容

- 您写入或选自提示词库的**提示词正文**及备注
- 从 AI 对话页面采集的**回复全文、回复 HTML**
- 按您选择生成的**视口截图、对话区长截图**等图像内容
- 可选的**关键词**及其匹配结果

#### 3.4 网络记录（与检测相关）

- 检测所涉及的 AI 平台名称、页面 URL / 域名及检测时间等元数据  
  （仅服务于您主动发起的检测任务，不用于构建与产品无关的全面浏览历史画像）

#### 3.5 位置相关信息

- 当本扩展与服务器通信时，服务器可能处理连接所需的 **IP 地址**及大致网络区域信息（用于安全、防滥用、运维与故障排查）

#### 3.6 其他运行数据

- 本机扩展配置、安装标识（如 installId）、检测批次/轮次状态、执行日志摘要
- 付费版可选上报的**异常现场**信息（用于排障；是否上报由您在异常时选择）

我们**不**通过本扩展收集健康信息、信用卡号等财务付款卡信息，也不将本扩展用于信用评估。

### 4. 数据如何存储：免费版与付费版

| 类型 | 免费版 | 付费版 |
|------|--------|--------|
| 登录 | 内置免费身份，无需个人邮箱密码 | 邮箱密码或访问令牌 |
| 检测结果 / 提示词 | 主要保存在**本机**（浏览器扩展存储） | 写入**云端**（默认 `geo.3biu.cn`） |
| 截图 | 边截边下载到本机；结果中通常不长期保留图片 | 可上传云端，便于结果页回看 |
| 异常 | 本机现场，不上报云端 | 可选择上报或不上报 |

即使数据仅保存在本机，也属于对本政策所述用户数据的「处理」。请妥善保管您的设备与浏览器配置文件。

### 5. 我们如何使用数据

我们仅将数据用于提供与改进 BiuEcho 的**单一用途**，包括：

1. 完成您发起的多平台 AI 对话可见度监测  
2. 账号鉴权、套餐/客户授权校验与会话维持  
3. 在侧栏与结果页展示、筛选、导出检测结果  
4. 安全防护、防滥用、故障排查与客户支持  
5. 履行适用法律法规要求  

我们不会将用户数据用于与上述单一用途无关的目的，不会用于确定信用度或贷款资格，也不会向第三方出售用户数据。

### 6. 共享与第三方

- **不出售**用户数据。  
- 为托管与运维本服务，数据可能由我们使用的云基础设施服务商代表我们处理（作为数据处理方），且仅限提供本服务所必需的范围。  
- 检测过程会在您选定的**第三方 AI 平台网页**中输入提示词；这些平台按其自身条款与隐私政策处理页面上的内容。本扩展不控制第三方 AI 平台的数据处理。  
- 在法律要求、保护用户或公众安全、或保护我们合法权益所必要时，我们可能披露信息。

### 7. 保留期限

- **本机数据**：保留至您清除扩展数据、卸载扩展，或达到产品设置的本地历史/提示词条数上限被轮换删除。  
- **云端数据**：在您的付费账号/客户关系存续期间，按业务需要保留；账号关闭或您提出删除请求后，我们将在合理期限内删除或匿名化，法律另有要求的除外。  

### 8. 安全措施

- 客户端与服务器之间的数据传输使用 **HTTPS** 等加密传输。  
- 我们采取合理的组织与技术措施保护数据，但无法保证绝对安全。请勿与他人分享您的密码或访问令牌。

### 9. 您的选择与权利

您可以：

- 在选项页退出登录、更换令牌或清除本机相关配置  
- 删除本机或云端提示词/历史（在产品能力范围内）  
- 卸载本扩展以停止新的数据采集  
- 通过 service@3biu.cn 请求查阅、更正、导出或删除云端账号相关数据  

请注意：删除云端数据可能影响您继续使用付费功能；第三方 AI 平台上已产生的对话内容需按该平台规则处理。

### 10. 儿童

本扩展面向企业与专业用户场景，不面向 13 岁以下儿童（或您所在司法辖区规定的更高年龄）。我们不会故意收集儿童的个人数据。

### 11. 国际传输

若您位于中国大陆以外地区，或服务器部署涉及跨境传输，您的数据可能在相关法域进行处理。我们将在适用法律要求的范围内采取适当保护措施。

### 12. Chrome 网上应用店用户数据政策（Limited Use）

本扩展对用户数据的使用将遵守 [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq)，包括 Limited Use 要求：仅将所收集的用户数据用于提供或改进本扩展的单一用途功能，不为无关目的出售或转移用户数据，不为信用评估或贷款目的使用用户数据。

### 13. 政策更新

我们可能不时更新本政策。更新后将修改文首「生效日期」，并在可行时通过产品页面或邮件提示。继续使用本扩展即视为知悉更新后的政策。

---

## English

### 1. Overview

BiuEcho (the “Extension” / “Service”) helps you run configured prompts on selected AI chat websites, capture replies and screenshots, and optionally match keywords to measure brand or keyword visibility in AI answers.

This Policy explains how we collect, use, store, share, and protect related user data. By using the Extension, you acknowledge these practices. If you disagree, stop using and uninstall the Extension.

### 2. Operator & contact

- Product: BiuEcho  
- Default data service host: `https://geo.3biu.cn`  
- Email: service@3biu.cn  

To access, correct, export, or delete cloud data associated with your account, or for privacy questions, contact us at the email above.

### 3. Data we may collect

Depending on free vs paid use and the detection options you enable, we may process:

#### 3.1 Personally identifiable information

- **Email address** used for paid sign-in  
- Customer / plan identifiers needed for authorization  

#### 3.2 Authentication information

- **Password** submitted for email login (sent over HTTPS; never publicly displayed)  
- Access **tokens / credentials** used to maintain a session  

#### 3.3 Website content & user-generated content

- **Prompt text** and notes you create or select  
- **Full reply text and HTML** captured from AI chat pages  
- **Screenshots** (viewport and/or long conversation captures) you choose to collect  
- Optional **keywords** and match results  

#### 3.4 Web history (task-related)

- AI platform names, page **URLs / domains**, and timestamps related to detection runs you start  
  (Not used to build unrelated full browsing profiles)

#### 3.5 Location-related

- **IP address** and coarse network region information that may be processed when the Extension communicates with our servers (security, abuse prevention, operations, troubleshooting)

#### 3.6 Other operational data

- Local settings, install identifiers, batch/round status, execution log summaries  
- Optional paid-tier **incident** payloads you choose to report for troubleshooting  

We do **not** collect health data or payment card numbers through the Extension, and we do not use the Extension for creditworthiness determinations.

### 4. Storage: Free vs Paid

| | Free | Paid |
|--|------|------|
| Sign-in | Built-in free identity | Email/password or access token |
| Results / prompts | Primarily **on-device** | Stored in the **cloud** (default `geo.3biu.cn`) |
| Screenshots | Downloaded locally during runs | May upload for later review |
| Incidents | Local only | Optional cloud report |

On-device storage still constitutes handling of user data under this Policy.

### 5. How we use data

We use data only to provide and improve BiuEcho’s **single purpose**, including:

1. Running multi-platform AI visibility detection you initiate  
2. Authentication, authorization, and session maintenance  
3. Showing, filtering, and exporting results in the UI  
4. Security, abuse prevention, troubleshooting, and support  
5. Compliance with applicable law  

We do not sell user data, use it for unrelated purposes, or use it to determine creditworthiness or for lending.

### 6. Sharing

- We do **not sell** user data.  
- Cloud infrastructure providers may process data on our behalf solely to host and operate the Service.  
- Detection interacts with **third-party AI websites** under their own terms and privacy policies.  
- We may disclose information when required by law or necessary to protect users, the public, or our legitimate rights.

### 7. Retention

- **On-device data**: until you clear extension data, uninstall, or local limits rotate older items out.  
- **Cloud data**: while your paid account/customer relationship is active; after closure or a deletion request, we delete or anonymize within a reasonable period unless law requires longer retention.

### 8. Security

We transmit data between the client and our servers using **HTTPS** and apply reasonable safeguards. No method is 100% secure. Do not share passwords or tokens.

### 9. Your choices

You may sign out, rotate tokens, delete prompts/history within product capabilities, uninstall the Extension, or email service@3biu.cn to request access, correction, export, or deletion of cloud account data.

### 10. Children

The Extension is intended for business/professional use and not for children under 13 (or a higher age required in your jurisdiction). We do not knowingly collect children’s personal data.

### 11. International transfers

Data may be processed in jurisdictions where we or our providers operate. We take steps required by applicable law for such transfers.

### 12. Chrome Web Store Limited Use

Use of information received through the Extension complies with the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data-faq), including the Limited Use requirements.

### 13. Changes

We may update this Policy and revise the effective date above. Continued use after an update means you acknowledge the revised Policy.
