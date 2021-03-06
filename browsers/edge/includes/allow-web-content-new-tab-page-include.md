---
author: shortpatti
ms.author: pashort
ms.date:  10/02/2018
ms.prod: edge
ms:topic: include
---

<!-- ## Allow web content on New Tab page -->  
>*Supported versions: Microsoft Edge on Windows 10*<br>
>*Default setting:  Enabled (Default New Tab page loads)*


[!INCLUDE [allow-web-content-on-new-tab-page-shortdesc](../shortdesc/allow-web-content-on-new-tab-page-shortdesc.md)]


### Supported values

|Group Policy  |MDM |Registry |Description |
|---|:---:|:---:|---|
|Not configured |Blank |Blank |Users can choose what loads on the New Tab page. | 
|Disabled |0 |0 |Load a blank page instead of the default New Tab page and prevent users from changing it. | 
|Enabled **(default)** |1 |1 |Load the default New Tab page. | 
---

### ADMX info and settings

#### ADMX info
- **GP English name:** Allow web content on New Tab page
- **GP name:** AllowWebContentOnNewTabPage
- **GP path:** Windows Components/Microsoft Edge
- **GP ADMX file name:** MicrosoftEdge.admx

#### MDM settings
- **MDM name:** Browser/[AllowWebContentOnNewTabPage](https://docs.microsoft.com/windows/client-management/mdm/policy-csp-browser#browser-allowwebcontentonnewtabpage)
- **Supported devices:** Desktop
- **URI full path:** ./Vendor/MSFT/Policy/Config/Browser/AllowWebContentOnNewTabPage 
- **Data type:** Integer

#### Registry settings
- **Path:** HKLM\\Software\\Policies\\Microsoft\\MicrosoftEdge\\ServiceUI
- **Value name:** AllowWebContentOnNewTabPage
- **Value type:** REG_DWORD

### Related policies
[Set New Tab page URL](../available-policies.md#set-new-tab-page-url): [!INCLUDE [set-new-tab-url-shortdesc](../shortdesc/set-new-tab-url-shortdesc.md)]

<hr>