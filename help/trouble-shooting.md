---
title: 故障排除控制面板
description: 了解如何对控制面板进行故障排除。
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
source-git-commit: dc31bc114b82eae4042562f292d5f52203c7e2b3
workflow-type: tm+mt
source-wordcount: '320'
ht-degree: 100%

---

# 故障排除 [!UICONTROL Control Panel]

## 登录和主页

### 症状：无法登录 Experience Cloud

**要做什么：**
用户须找到其 IMS Org ID (xxx)。管理员须将用户添加到要管理的每个实例的产品用户档案“Campaign-xxx-Admins”中。如果用户是所有实例的管理员，他们仍须将自己添加为用户。

### 症状：Experience Cloud 主页中访问 [!UICONTROL Control Panel] 的链接不显示给用户

**原因：**
用户只有在被添加为产品用户档案 _Campaign-xxx-Administrators/Admin_ 中的用户后，才会看到这些链接。

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品用户档案 _Campaign-xxx-Admins_ 中。如果用户是所有实例的管理员，他们仍须将自己添加为用户。

### 症状：实例未列在 [!UICONTROL Control Panel] 中

**原因：**
最可能的原因是，对于缺少的实例，须将用户在产品用户档案 _Campaign-xxx-Administrators/Admin_ 中添加为&#x200B;*用户*

**要做什么：**
管理员须将用户添加到要管理的每个实例的产品用户档案 _Campaign-xxx-Admins_ 中。如果用户是所有实例的管理员，他们须将自己添加为“用户”。

### 实用视频

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*查找 IMS Org ID（00:26 分）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何将管理员在产品用户档案中添加为管理员，以便能够使用[!UICONTROL Control panel]（1 分 3 秒）*

### 帮助文档

* [了解控制面板](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hans)
* [管理 [!UICONTROL Control Panel]的权限](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## 建立与 SFTP 服务器（客户端或 API）的连接

连接到 SFTP 服务器需要：

* [!UICONTROL Allow listing] 您连接到 SFTP 服务器的 IP 地址
* 须在 Adobe Campaign 中注册的私钥/公钥对
* 要直接连接到 SFTP 服务器，您还需要有 SFTP 客户端软件

### 帮助文档 {#helpful-docs}

* [登录 SFTP 服务器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)
