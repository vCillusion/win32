---
description: The put\_ScaleX method specifies the amount by which the wipe is stretched horizontally.
ms.assetid: d57af5dc-41e0-45a7-8f11-55ef3bc62549
title: IDxtJpeg::put_ScaleX method (Qedit.h)
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IDxtJpeg.put_ScaleX
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
---

# IDxtJpeg::put\_ScaleX method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `put_ScaleX` method specifies the amount by which the wipe is stretched horizontally.

## Syntax


```C++
HRESULT put_ScaleX(
  [in] double newVal
);
```



## Parameters

<dl> <dt>

*newVal* \[in\]
</dt> <dd>

The amount by which the wipe is stretched horizontally, as a percentage of the original wipe definition. For example, the value 1.0 means no stretching, and 2.0 means 200% stretching.

</dd> </dl>

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Remarks

> [!Note]  
> The header file Qedit.h is not compatible with Direct3D headers later than version 7.

 

> [!Note]  
> To obtain Qedit.h, download the [Microsoft Windows SDK Update for Windows Vista and .NET Framework 3.0](https://msdn.microsoft.com/windowsvista/bb980924.aspx). Qedit.h is not available in the Microsoft Windows SDK for Windows 7 and .NET Framework 3.5 Service Pack 1.

 

## Requirements



|                    |                                                                                         |
|--------------------|-----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>Qedit.h</dt> </dl>      |
| Library<br/> | <dl> <dt>Strmiids.lib</dt> </dl> |



## See also

<dl> <dt>

[**IDxtJpeg Interface**](idxtjpeg.md)
</dt> </dl>

 

 




