---
title: 添加 SSL 证书
description: 了解如何添加 SSL 证书以保护子域。
feature: Control Panel
jira: KT-4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
TQID: 'https://experienceleague.adobe.com/0bt8fHWusGHKrXc-ireqA25Eo75SA2pCj9MhADcHBxA'
product_v2:
  - id: dfc56824-e8b9-499e-85d4-21aedb507314
    internal-label: Campaign
feature_v2:
  - id: ae9127b0-c11d-467b-903d-a84cef43f6ed
    internal-label: Control Panel
role_v2:
  - id: c66ffd68-0f65-42bb-aa23-b4020f12e0bd
    internal-label: Admin
level_v2:
  - id: d378ca77-2da1-4f39-ad92-1917fe974a38
    internal-label: Experienced
source-git-commit: e4a8e51ee4016895090eb90d528d0a2707fd0225
workflow-type: tm+mt
source-wordcount: '290'
ht-degree: 95%
---
# 添加 SSL 证书

Adobe Campaign [!UICONTROL 控制面板]允许您添加 SSL 证书以保护子域。

## 访问控制面板子域管理

要在控制面板中访问子域管理，请转到：

* [Experience Cloud 主页](https://experience.adobe.com/#/home) > 解决方案选择器：**[!DNL Campaign]** > **[!UICONTROL 控制面板]**&#x200B;信息卡 > **[!UICONTROL 子域和证书]**&#x200B;信息卡

  或者
* 直接从 URL 访问：[https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## 添加 SSL 证书的步骤

添加 SSL 证书需要三个步骤：

### &#x200B;1. 生成证书签名请求

购买 SSL 证书需要证书签名请求 (CSR)。 您需要为计划保护的实例和子域生成 CSR。

以下视频介绍如何在控制面板中生成证书签名请求。

>[!VIDEO](https://video.tv.adobe.com/v/35898?captions=chi_hans&learn=on){transcript=true}

*生成证书签名请求（02:36分钟）*

>[!NOTE]
>
>对 CSR 生成过程进行了一些增强：
>
>* 现在，在生成 CSR 时，您可以选择其中一个包含的子域作为通用名称。
>* 现在，您可以在生成 CSR 之前复制 CSR 摘要。
>* 生成 CSR 后，您可以从作业日志中再次下载它。 此功能不适用于在此版本之前生成的证书。
>
>![下载 CSR](/help/assets/download-csr.gif)
>
>请参阅[产品文档](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=zh-Hans)以了解更多信息。
>

### &#x200B;2. 购买 SSL 证书

获得 CSR 后，您需要从您组织批准的证书颁发机构购买 SSL 证书。

### &#x200B;3. 安装 SSL 证书

获得 SSL 证书后，必须为您计划保护的子域安装该证书。

以下视频介绍如何在[!UICONTROL 控制面板]中安装 SSL 证书。

>[!VIDEO](https://video.tv.adobe.com/v/35899?captions=chi_hans&learn=on){transcript=true}

*安装SSL证书（01:25分钟）*


