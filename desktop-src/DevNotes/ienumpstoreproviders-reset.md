---
Description: Resets to the beginning of the enumeration sequence.
ms.assetid: 9c5044b5-25a3-4d10-829b-ef4d8b5ac095
title: IEnumPStoreProviders::Reset method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# IEnumPStoreProviders::Reset method

\[Protected Storage (Pstore) is available for use in Windows Server 2003 and Windows XP. It is only available for read-only operations in Windows Server 2008 and Windows Vista, but may be unavailable in subsequent versions. Pstore uses an older implementation of data protection. Developers are strongly encouraged to take advantage of the stronger data protection provided by the [**CryptProtectData**](https://msdn.microsoft.com/windows/desktop/765a68fd-f105-49fc-a738-4a8129eb0770) and [**CryptUnprotectData**](https://msdn.microsoft.com/windows/desktop/54eab3b0-d341-47c6-9c32-79328d7a7155) functions.\]

Resets to the beginning of the enumeration sequence.

## Syntax


```C++
HRESULT Reset();
```



## Parameters

This method has no parameters.

## Return value

The return value is an **HRESULT** value.

## Requirements



|                   |                                                                                        |
|-------------------|----------------------------------------------------------------------------------------|
| Header<br/> | <dl> <dt>Pstore.h</dt> </dl>    |
| DLL<br/>    | <dl> <dt>Pstorec.dll</dt> </dl> |



## See also

<dl> <dt>

[**IEnumPStoreProviders**](ienumpstoreproviders.md)
</dt> </dl>

 

 



