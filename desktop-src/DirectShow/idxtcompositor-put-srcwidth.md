---
Description: The put\_SrcWidth method specifies the width of the source rectangle.
ms.assetid: 3dbf8ddb-1da9-468f-9960-30e7b8c305e0
title: IDxtCompositor::put_SrcWidth method (Qedit.h)
ms.topic: reference
ms.date: 05/31/2018
topic_type: 
- APIRef
- kbSyntax
api_name: 
- IDxtCompositor.put_SrcWidth
api_type: 
- COM
api_location: 
- strmiids.lib
- strmiids.dll
---

# IDxtCompositor::put\_SrcWidth method

> [!Note]  
> \[Deprecated. This API may be removed from future releases of Windows.\]

 

The `put_SrcWidth` method specifies the width of the source rectangle.

## Syntax


```C++
HRESULT put_SrcWidth(
  [in] long newVal
);
```



## Parameters

<dl> <dt>

*newVal* \[in\]
</dt> <dd>

The width of the source rectangle, in pixels.

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

[**IDxtCompositor Interface**](idxtcompositor.md)
</dt> </dl>

 

 




