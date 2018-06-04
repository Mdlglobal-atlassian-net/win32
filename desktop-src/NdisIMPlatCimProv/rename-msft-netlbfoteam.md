---
Description: Renames a team.
ms.assetid: f678acf2-eb3a-40c1-9bf7-1fe3c63947bf
title: Rename method of the MSFT\_NetLbfoTeam class
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# Rename method of the MSFT\_NetLbfoTeam class

Renames a team.

## Syntax


```mof
uint32 Rename(
  [in]  string           Name,
  [in]  string           NewName,
  [out] MSFT_NetLbfoTeam CmdletOutput
);
```



## Parameters

<dl> <dt>

*Name* \[in\]
</dt> <dd>

Specifies the name of the team that you want to rename.

</dd> <dt>

*NewName* \[in\]
</dt> <dd>

Specifies the new name for the team.

</dd> <dt>

*CmdletOutput* \[out\]
</dt> <dd>

Receives a [**MSFT\_NetLbfoTeam**](msft-netlbfoteam.md) object that represents the renamed team.

</dd> </dl>

## Requirements



|                                     |                                                                                                |
|-------------------------------------|------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 8<br/>                                                                           |
| Minimum supported server<br/> | Windows Server 2012<br/>                                                                 |
| Namespace<br/>                | Root\\StandardCimv2<br/>                                                                 |
| Header<br/>                   | <dl> <dt>Corecrt\_io.h</dt> </dl>       |
| MOF<br/>                      | <dl> <dt>MsNetImPlatform.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>NdisIMPlatCim.dll</dt> </dl>   |



## See also

<dl> <dt>

[**MSFT\_NetLbfoTeam**](msft-netlbfoteam.md)
</dt> </dl>

 

 



