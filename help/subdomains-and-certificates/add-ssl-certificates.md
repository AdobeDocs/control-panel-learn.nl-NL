---
title: SSL-certificaten toevoegen
description: Leer hoe u SSL-certificaten toevoegt om uw subdomeinen te beveiligen.
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

# SSL-certificaten toevoegen

In het [!UICONTROL Control Panel] van Adobe Campaign kunt u SSL-certificaten toevoegen om uw subdomeinen te beveiligen.

## Toegang tot subdomeinbeheer in het Configuratiescherm

Om toegang te krijgen tot subdomeinbeheer in het Configuratiescherm gaat u naar:

* [Experience Cloud Home](https://experience.adobe.com/#/home) > Oplossingskiezer: **[!DNL Campaign]** > kaart **[!UICONTROL Control Panel]** > kaart **[!UICONTROL Subdomains & Certificates]**

   of
* Rechtstreeks via de URL: [https://experience.adobe.com/#/controlpanel/domain](https://experience.adobe.com/#/controlpanel/domain)

## Stappen om SSL-certificaten toe te voegen

Voor het toevoegen van SSL-certificaten zijn drie stappen vereist:

### 1. Aanvragen voor certificaatondertekening genereren

De CSR (Certificate Signing Request) is vereist voor de aanschaf van een SSL-certificaat. Deze moet worden gegenereerd voor de instantie en de subdomeinen die u wilt beveiligen.

In de onderstaande video wordt beschreven hoe u een aanvraag voor certificaatondertekening kunt genereren in het Configuratiescherm.

>[!VIDEO](https://video.tv.adobe.com/v/31317?quality=12)

*Aanvragen voor certificaatondertekening genereren (02:36 min)*

>[!NOTE]
>
>Er zijn verschillende verbeteringen aangebracht in het CSR-generatieproces:
>
>* Wanneer het produceren van CSR, kunt u één van inbegrepen subdomeinen nu selecteren als Gemeenschappelijke Naam.
>* U kunt het overzicht CSR nu kopiëren alvorens CSR te produceren.
>* Nadat een CSR is gegenereerd, kunt u deze opnieuw downloaden uit de taaklogboeken. Deze functie is niet van toepassing op certificaten die zijn gegenereerd vóór deze release.
>
>![CSR downloaden](/help/assets/download-csr.gif)
>
>Zie de [productdocumentatie](https://experienceleague.adobe.com/docs/control-panel/using/subdomains-and-certificates/renew-ssl/renewing-subdomain-certificate.html?lang=en) voor meer informatie.

### 2. SSL-certificaat aanschaffen

Nadat u de CSR hebt verkregen, moet u het SSL-certificaat aanschaffen bij een certificeringsinstantie die is goedgekeurd door uw organisatie.

### 3. SSL-certificaten installeren

Nadat u het SSL-certificaat hebt verkregen, moet het worden geïnstalleerd voor de subdomeinen die u wilt beveiligen.

In de onderstaande video ziet u hoe u SSL-certificaten kunt installeren in [!UICONTROL Control Panel].

>[!VIDEO](https://video.tv.adobe.com/v/31166?quality=12)

*SSL-certificaten installeren (01:25 min)*


