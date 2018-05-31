---
Description: The code for broadcasting a fax is identical to the code for sending a fax, except for the change in the number of recipients. For each recipient you would add another line of code in the following format.
ms.assetid: d0794565-9ee3-44c8-8959-b082b6f86854
title: Broadcasting a Fax (C++)
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Broadcasting a Fax (C++)

The code for broadcasting a fax is identical to the code for [sending a fax](-mfax-sending-a-fax.md), except for the change in the number of recipients. For each recipient you would add another line of code in the following format.


```
sipFaxDocument -> Recipients -> Add (RECIPIENT_PHONE_NUMBER,RECIPIENT_NAME);
```



 

 


