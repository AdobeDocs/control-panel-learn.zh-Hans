---
title: 新增SSL憑證
description: 瞭解如何新增SSL憑證以保護您的子網域。
feature: Control Panel
kt: 4219
thumbnail: 31317.jpg
doc-type: feature video
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 7937499a-8267-4ce6-a93c-65c0c5e4e582
source-git-commit: 1b1efe35c2ddcf379d1e847064ffa8be18d276b3
workflow-type: tm+mt
source-wordcount: '269'
ht-degree: 58%

---

# 新增SSL憑證

Adobe Campaign [!UICONTROL Control Panel] 允许您添加 SSL 证书以保护子域。

## 访问控制面板子域管理

要在控制面板中访问子域管理，请转到：

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Solution picker: **[!DNL Campaign]** > **[!UICONTROL Control Panel]** card > **[!UICONTROL Subdomains & Certificates]** card

   或者
* 直接从 URL 访问：[https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## 添加 SSL 证书的步骤

添加 SSL 证书需要三个步骤：

### 1. 生成证书签名请求

購買SSL憑證需要憑證簽署要求(CSR)。 必須為您打算保護的執行個體和子網域產生它。

以下视频介绍如何在控制面板中生成证书签名请求。

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12&learn=0n)

*生成证书签名请求（02:36 分钟）*

>[!NOTE]
>
>CSR產生程式已進行幾項增強：
>
>* 现在，在生成 CSR 时，您可以选择其中一个包含的子域作为通用名称。
>* 现在，您可以在生成 CSR 之前复制 CSR 摘要。
>* 生成 CSR 后，您可以从作业日志中再次下载它。此功能不适用于在此版本之前生成的证书。
>
>![下載CSR](/help/assets/download-csr.gif)
>
>請參閱 [產品檔案](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=en) 以深入瞭解。

### 2. 购买 SSL 证书

取得CSR後，您必須向貴組織核准的憑證機構購買SSL憑證。

### 3. 安装 SSL 证书

取得SSL憑證後，必須為您計畫保護的子網域安裝該憑證。

以下视频介绍如何在 [!UICONTROL Control Panel]中安装 SSL 证书。

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12&learn=0n)

*安装 SSL 证书（01:25 分钟）*


