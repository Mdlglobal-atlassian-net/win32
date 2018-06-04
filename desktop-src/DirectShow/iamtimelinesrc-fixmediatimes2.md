---
Description: The FixMediaTimes2 method rounds the specified time values to the nearest frame boundary, as defined by the output frame rate. This method is equivalent to IAMTimelineSrc::FixMediaTimes, but takes REFTIME values.
ms.assetid: c51172ea-b5d7-4a2e-ace2-85e6e671c1e9
title: IAMTimelineSrc::FixMediaTimes2 method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# IAMTimelineSrc::FixMediaTimes2 method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `FixMediaTimes2` method rounds the specified time values to the nearest frame boundary, as defined by the output frame rate. This method is equivalent to [**IAMTimelineSrc::FixMediaTimes**](iamtimelinesrc-fixmediatimes.md), but takes [**REFTIME**](reftime.md) values.

## Syntax


```C++
HRESULT FixMediaTimes2(
   REFTIME *pStart,
   REFTIME *pStop
);
```



## Parameters

<dl> <dt>

*pStart* 
</dt> <dd>

Pointer to a variable that contains the start time, in seconds. If the call succeeds, this variable is set to the rounded time.

</dd> <dt>

*pStop* 
</dt> <dd>

Pointer to a variable that contains the stop time, in seconds. If the call succeeds, this variable is set to the rounded time.

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](http://go.microsoft.com/fwlink/p/?linkid=129787). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IAMTimelineSrc Interface**](iamtimelinesrc.md)
</dt> <dt>

[Error and Success Codes](error-and-success-codes.md)
</dt> </dl>

 

 



