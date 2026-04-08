---
title: 故障排除控制面板
description: 了解如何对控制面板进行故障排除。
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
source-git-commit: 81c5210502e719d6dfe0a000c511e3da4b17275a
workflow-type: ht
source-wordcount: '353'
ht-degree: 100%

---

# 对[!UICONTROL 控制面板]进行故障排除

## 登录和主页

### 症状：无法登录 Experience Cloud

**要做什么：**
用户须找到其 IMS Org ID (xxx)。 管理员须将用户添加到要管理的每个实例的产品配置文件“Campaign-xxx-Admins”中。 如果用户是所有实例的管理员，他们仍须将自己添加为用户。

### 症状：Experience Cloud 主页中的用于访问[!UICONTROL 控制面板]的链接未向某个用户显示

**原因：**
用户只有在被添加为产品配置文件 _Campaign-xxx-Administrators/Admin_ 中的用户后，才会看到这些链接。

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品配置文件 _Campaign-xxx-Admins_ 中。 如果用户是所有实例的管理员，他们仍须将自己添加为用户。

### 症状：实例未在[!UICONTROL 控制面板]中列出

**原因：**
最可能的原因是，对于缺少的实例，须将用户在产品配置文件 _Campaign-xxx-Administrators/Admin_ 中添加为&#x200B;*用户*

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品配置文件 _Campaign-xxx-Admins_ 中。 如果用户是所有实例的管理员，他们须将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/27183?learn=on){transcript=true}

*检查 IMS 组织 ID（00:26 分钟）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?learn=on){transcript=true}

*如何向产品配置文件管理员添加管理员，以便能够使用[!UICONTROL 控制面板]（01:03 分钟）*

### 帮助文档

* [了解控制面板](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)
* [管理[!UICONTROL 控制面板]的使用权限](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)

## 建立与 SFTP 服务器（客户端或 API）的连接

连接到 SFTP 服务器需要：

* [!UICONTROL 将]您连接到 SFTP 服务器时的 IP 地址添加到允许列表
* 须在 Adobe Campaign 中注册的私钥/公钥对
* 要直接连接到 SFTP 服务器，您还需要有 SFTP 客户端软件

### 帮助文档 {#helpful-docs}

* [登录 SFTP 服务器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)
