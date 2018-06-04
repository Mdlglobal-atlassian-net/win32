---
Description: Constructor method.
ms.assetid: 2982f53a-c222-4a9d-812a-42897ca4cb5c
title: CBaseList.CBaseList constructor
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# CBaseList.CBaseList constructor

Constructor method.

## Syntax


```C++
CBaseList(
   TCHAR *pName
);
```



## Parameters

<dl> <dt>

*pName* 
</dt> <dd>

Pointer to the name of the list.

</dd> </dl>

## Remarks

For efficiency, the `CBaseList` class maintains a cache of list nodes. This version of the constructor uses a default cache size.

## Requirements



|                    |                                                                                                                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Wxlist.h (include Streams.h)</dt> </dl>                                                                                    |
| Library<br/> | <dl> <dt>Strmbase.lib (retail builds); </dt> <dt>Strmbasd.lib (debug builds)</dt> </dl> |



## See also

<dl> <dt>

[**CBaseList Class**](cbaselist.md)
</dt> </dl>

 

 



