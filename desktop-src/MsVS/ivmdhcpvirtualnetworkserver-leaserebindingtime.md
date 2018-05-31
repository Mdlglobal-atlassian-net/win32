---
error-parsing-yaml: 
---

# IVMDHCPVirtualNetworkServer::LeaseRebindingTime property

The **LeaseRebindingTime** property contains the time in seconds after which the client virtual machine should rebind if the virtual DHCP server has not responded.

This property is read-only.

## Syntax


```C++
HRESULT get_LeaseRebindingTime(
  [out] VARIANT *leaseRebindingTime
);
```

<span codelanguage="VisualBasic"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>VB</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre><code>VMDHCPVirtualNetworkServer.LeaseRebindingTime( _
  ByRef leaseRebindingTime _
)</code></pre></td>
</tr>
</tbody>
</table>



## Property value

The lease rebinding time in seconds. The minimum value for this parameter is 45 seconds. The number is returned as a **Decimal** value.

This property value is read-only.

## Error codes



| Name                                                                                          | Meaning                                                     |
|-----------------------------------------------------------------------------------------------|-------------------------------------------------------------|
| <dl> <dt>S\_OK</dt> </dl>              | The operation was successful.<br/>                    |
| <dl> <dt>E\_POINTER</dt> </dl>         | The *leaseRebindingTime* parameter was **NULL**.<br/> |
| <dl> <dt>DISP\_E\_EXCEPTION</dt> </dl> | An unexpected error has occurred.<br/>                |



## Requirements



|                     |                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------|
| Product<br/>  | Microsoft Virtual Server 2005 onWindows Server 2003<br/>                                    |
| Download<br/> | Microsoft Virtual Server 2005 R2 SP1 Update onWindows Server 2008orWindows Server 2003<br/> |
| Header<br/>   | <dl> <dt>VsComInterfaces.h</dt> </dl>      |



## See also

<dl> <dt>

[**IVMDHCPVirtualNetworkServer**](ivmdhcpvirtualnetworkserver.md)
</dt> </dl>

 

 




