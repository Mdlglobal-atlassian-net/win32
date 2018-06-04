---
title: ATA Port Routines for Registry Access
description: ATA Port Routines for Registry Access
ms.assetid: 36d483b3-66b1-43ac-bc76-31405108f349
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# ATA Port Routines for Registry Access

## 

This section discusses routines that a miniport driver uses to access the Windows registry. Only miniport drivers that implement the channel interface can call these routines. Miniport drivers that only implement the controller interface routines cannot access these routines.

> [!Note]  
> The ATA port driver and ATA miniport driver models may be altered or unavailable in the future. Instead, we recommend using the [Storport driver](https://msdn.microsoft.com/windows/hardware/drivers/storage/storport-driver) and [Storport miniport](https://msdn.microsoft.com/windows/hardware/drivers/storage/storport-miniport-drivers) driver models.

 

This section includes the following routines:

<dl>

[**AtaPortRegistryAllocateBuffer**](ataportregistryallocatebuffer.md)  
[**AtaPortRegistryFreeBuffer**](ataportregistryfreebuffer.md)  
[**AtaPortRegistryControllerKeyRead**](ataportregistrycontrollerkeyread.md)  
[**AtaPortRegistryContrlollerKeyWrite**](ataportregistrycontrollerkeywrite.md)  
[**AtaPortRegistryControllerKeyWriteDeferred**](ataportregistrycontrollerkeywritedeferred.md)  
[**AtaPortRegistryChannelSubKeyRead**](ataportregistrychannelsubkeyread.md)  
[**AtaPortRegistryChannelSubKeyWrite**](ataportregistrychannelsubkeywrite.md)  
[**AtaPortRegistryChannelSubKeyWriteDeferred**](ataportregistrychannelsubkeywritedeferred.md)  
</dl>

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bstorage\storage%5D:%20ATA%20Port%20Routines%20for%20Registry%20Access%20%20RELEASE:%20%283/29/2018%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



