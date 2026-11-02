Effective Date: November 2, 2026

"Liu Gao" (留稿) is a Chrome extension designed to save and restore text entered into web pages locally. This policy explains what data the extension processes, how that data is used, how it is stored, and how it can be deleted.

Data Processed

Once a user provides explicit authorization and enables protection for a specific website, the extension processes plain text and historical versions of text entered into supported input fields, editable areas, and certain table cells. It also collects field identifiers, labels, and necessary information about editable areas to ensure text is restored to the correct location.

Drafts are associated with the page URL, page title, and the time they were saved. While URLs are filtered to remove known sensitive parameters, it is not possible to guarantee the identification of sensitive parameters for every website.

Saved text may contain personal information—such as names, email addresses, phone numbers, or draft communications—as well as other sensitive content, including health, financial, or location-related data. The extension cannot reliably identify and exclude all such information.

The extension also stores website protection settings, records of user consent, rules for excluding specific input fields, and temporary information related to restoration operations.

Purpose of Data Use

The data described above is used exclusively for the following purposes: automatically saving web-based text, viewing drafts, restoring historical versions, matching text to the correct target fields, creating backups prior to restoration, and managing website authorization.

"Liu Gao" does not use this data for advertising, user profiling, credit assessment, or any analysis unrelated to the protection of web-based text input.

Storage and Sharing

Draft content and historical versions are stored locally within the extension’s own IndexedDB database in your browser. Settings are stored using `chrome.storage.local`, while certain temporary operational data is stored using `chrome.storage.session`.

The extension does not utilize a backend server to receive drafts, nor does it upload drafts to the developer. It does not use Chrome’s cloud synchronization feature, contains no telemetry or third-party analytics services, and does not sell user data.

When a user performs a restoration, the selected text is inserted back into the target web page. The target website may subsequently read, process, or submit this text; such actions are governed by that website’s own privacy policy.

Website Authorization and Sensitive Fields

The extension only saves text from websites for which the user has provided consent and granted access permissions.

Password fields are never saved, and the extension automatically skips fields identified as containing verification codes (CAPTCHAs), payment information, identification documents, or other sensitive data. This detection mechanism has limitations; please refrain from enabling protection on pages where you do not wish to keep local records. You may also use the "stop protection" feature for individual input fields.

"Draft Saver" (留稿) does not provide a "data vault" function and does not offer additional application-layer encryption for local drafts.

Retention and Deletion

Drafts are not automatically deleted based on the passage of time. Each draft retains up to 5 full-page versions, with a maximum of 20 content revisions stored per individual field. The total storage capacity is capped at 25 MB. Older records exceeding the version limit will be overwritten; once the storage limit is reached, users must clear existing records to continue saving new data.

Users can delete specific drafts or clear all drafts via the management page. Pausing protection or removing a website from the list does not automatically delete existing history. Uninstalling the extension will remove all of its local data. Users may also revoke a website's permissions through the Chrome extensions management interface.

Policy Changes

Should the extension’s data handling practices change, this policy and the disclosures provided on the Chrome Web Store will be updated accordingly.

Contact

For questions regarding privacy or data handling, please contact: japhetjiu699@gmail.com.

"Draft Saver" complies with the Chrome Web Store User Data Policy regarding the use of user data, including the "Limited Use" requirements.


** **


生效日期：2026 年 11 月 2 日

留稿是一款用于在本地保存和恢复网页输入文本的 Chrome 扩展。本政策说明扩展处理哪些数据，以及这些数据的用途、保存方式和删除方式。

**处理的数据**

在用户主动授权并开启网站保护后，留稿会处理支持的输入框、可编辑区域及部分表格单元格中的纯文本、文本历史版本，以及用于识别恢复目标的字段标识、标签和必要的编辑区域信息。

草稿还会关联页面网址、页面标题和保存时间。网址会经过部分已知敏感参数的过滤，但无法保证识别所有网站的敏感参数。

保存的文字可能包含用户输入的姓名、邮箱、电话、通讯草稿及其他个人信息。普通文本也可能包含健康、财务、位置或其他敏感内容，扩展无法可靠识别并排除所有此类信息。

扩展还会保存网站保护设置、用户同意记录、输入框排除规则及临时恢复操作信息。

**数据用途**

上述数据仅用于网页文本自动保存、草稿查看、历史版本恢复、目标字段匹配、恢复前备份及网站授权管理。

留稿不使用这些数据进行广告投放、用户画像、信用评估或与网页输入保护无关的分析。

**保存和共享**

草稿正文及历史版本保存在当前浏览器中扩展自己的 IndexedDB 数据库内。设置保存在 chrome.storage.local，部分临时操作信息保存在 chrome.storage.session。

扩展不设置接收草稿的后端服务器，不向开发者上传草稿，不使用 Chrome 云同步，不包含遥测或第三方分析服务，不出售用户数据。

用户执行恢复时，选中的文字会填回目标网页。目标网站可能读取、处理或提交这些文字，相关处理受该网站自身的隐私政策约束。

**网站授权和敏感字段**

扩展仅在用户同意并授予网站访问权限后，对开启保护的网站保存文本。

密码字段不保存，识别出的验证码、支付、证件及其他敏感字段会被跳过。此识别存在局限，请勿在不希望留下本地记录的页面开启保护，并可使用单个输入框的停止保护功能。

留稿不提供数据保险箱功能，不对本地草稿提供额外的应用层加密。

**保留和删除**

草稿不会仅因时间经过而自动删除。每份草稿最多保留 5 个整页版本，每个字段最多保留 20 次内容变化；总容量上限为 25 MB。超过版本数量的较旧记录会被替换，容量达到上限时需要用户清理记录后继续保存。

用户可以在管理页删除指定草稿，或清空全部草稿。暂停保护或移除网站不会自动删除已有历史。卸载扩展会删除该扩展的本地数据。用户也可以在 Chrome 的扩展管理界面撤销网站权限。

**政策变更**

扩展的数据处理方式发生变化时，本政策及商店披露信息将相应更新。

**联系**

如有隐私或数据处理问题，请联系：**japhetjiu699@gmail.com**。

留稿对用户数据的使用遵守 Chrome 应用商店用户数据政策，包括其中的“有限使用”要求。
