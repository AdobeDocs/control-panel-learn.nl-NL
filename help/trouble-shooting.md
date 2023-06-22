---
title: Problemen met het configuratiescherm oplossen
description: Ontdek hoe u problemen met het configuratiescherm kunt oplossen.
feature: Control Panel
jira: KT-2938
doc-type: article
activity: use
team: PM
role: Admin
level: Experienced
exl-id: 92d32589-7763-4895-8117-abfd47d808e3
source-git-commit: af05bde1295913c93388dd014462e32afb081669
workflow-type: ht
source-wordcount: '320'
ht-degree: 100%

---

# Problemen oplossen [!UICONTROL Control Panel]

## Aanmelding en startpagina

### Probleem: kan niet aanmelden bij Experience Cloud

**Wat moet u doen:**
De gebruiker moet de IMS-organisatie-id (xxx) zoeken. De beheerder moet de gebruiker toevoegen aan het productprofiel ‘Campaign-xxx-Admins’ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle versies is, moet deze ook zichzelf toevoegen als gebruiker.

### Symptoom: Koppelingen in de Experience Cloud Home voor toegang tot [!UICONTROL Control Panel] worden niet weergegeven voor een gebruiker

**Oorzaak:**
Gebruikers zien de koppelingen pas wanneer ze als gebruikers zijn toegevoegd aan het productprofiel _Campaign-xxx-Administrators/Admin_.

**Wat moet u doen:**
De beheerder moet de gebruiker toevoegen aan het productprofiel _Campaign-xxx-Admins_ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle versies is, moet deze ook zichzelf toevoegen als gebruiker.

### Symptoom: Een instantie wordt niet vermeld in het [!UICONTROL Control Panel]

**Oorzaak:**
Waarschijnlijk moet de gebruiker worden toegevoegd als *gebruiker* voor het productprofiel _Campaign-xxx-Administrators/Admin_ voor de ontbrekende versie

**Wat moet u doen:**
De beheerder moet de gebruiker toevoegen aan het productprofiel _Campaign-xxx-Admins_ voor elke versie die deze wil beheren. Als de gebruiker een beheerder van alle versies is, moet deze ook zichzelf toevoegen als &#39;gebruiker&#39;.

### Nuttige video’s

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12&learn=0n)

*IMS-organisatie-id controleren (00:26 min)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12&learn=0n)

*Een beheerder toevoegen aan het productprofiel voor beheerders om [!UICONTROL Control panel] te kunnen gebruiken (01:03 min)*

### Nuttige documentatie

* [Het Configuratiescherm verkennen](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)
* [Machtigingen beheren voor het [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)

## Verbinding met SFTP-server tot stand brengen (client of API)

Voor verbinding met SFTP-servers is het volgende vereist:

* [!UICONTROL Allow listing] het IP-adres waarvan u verbinding maakt met de SFTP-server
* Persoonlijk/openbaar sleutelpaar dat bij Adobe Campaign moet zijn geregistreerd
* Als u rechtstreeks verbinding maakt met de SFTP-server, hebt u ook SFTP-clientsoftware nodig

### Nuttige documentatie {#helpful-docs}

* [Aanmelden bij uw SFTP-server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=nl)
