---
title: 添加SSL证书
description: 了解如何添加SSL证书以保护子域。
feature: Control Panel
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: d12902547ffde67838b326c93162d0937ff438a6
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 38%

---

# 添加SSL证书

Adobe Campaign [!UICONTROL Control Panel] 允许您添加 SSL 证书以保护子域。

## 访问控制面板子域管理

要在控制面板中访问子域管理，请转到：

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Solution picker: **[!DNL Campaign]** > **[!UICONTROL Control Panel]** card > **[!UICONTROL Subdomains & Certificates]** card

   或者
* 直接从 URL 访问：[https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## 添加 SSL 证书的步骤

添加 SSL 证书需要三个步骤：

### 1. 生成证书签名请求

购买SSL证书需要证书签名请求(CSR)。 必须为您计划保护的实例和子域生成该子域。

以下视频介绍如何在控制面板中生成证书签名请求。

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*生成证书签名请求（02:36 分钟）*

>[!NOTE]
>
>对CSR生成过程进行了多项增强：
>
>* 现在，在生成CSR时，您可以选择其中一个包含的子域作为通用名称。
>* 现在，您可以在生成CSR之前复制CSR摘要。
>* 生成CSR后，您可以从作业日志中再次下载它。 此功能不适用于在此版本之前生成的证书。
>
>![下载CSR](/help/assets/download-csr.gif)
>
>请参阅 [产品文档](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=en) 以了解更多。

### 2. 购买 SSL 证书

获取CSR后，您必须从贵组织批准的证书颁发机构购买SSL证书。

### 3. 安装 SSL 证书

获得SSL证书后，必须为您计划保护的子域安装该证书。

以下视频介绍如何在 [!UICONTROL Control Panel]中安装 SSL 证书。

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*安装 SSL 证书（01:25 分钟）*


