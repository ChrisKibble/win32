---
Description: 'Retrieves the vendor name of the IInkAnalysisRecognizer.'
ms.assetid: '62ff209e-2a34-4c04-90a0-661d06898298'
title: 'IInkAnalysisRecognizer::GetVendor method'
---

# IInkAnalysisRecognizer::GetVendor method

Retrieves the vendor name of the [**IInkAnalysisRecognizer**](iinkanalysisrecognizer.md).

## Syntax


```C++
HRESULT GetVendor(
  [out]�BSTR *pbstrVendor
);
```



## Parameters

<dl> <dt>

*pbstrVendor* \[out\]
</dt> <dd>

The name of the vendor.

</dd> </dl>

## Return value

For a description of the return values, see [Classes and Interfaces - Ink Analysis](classes-and-interfaces---ink-analysis.md).

## Remarks

> \[!Caution\]  
> To avoid a memory leak, call [**SysFreeString**](8f230ee3-5f6e-4cb9-a910-9c90b754dcd3) on \**pbstrVendor* when you no longer need to use the string.

�

## Requirements



|                                     |                                                                                                               |
|-------------------------------------|---------------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows�XP Tablet PC Edition \[desktop apps only\]<br/>                                                 |
| Minimum supported server<br/> | None supported<br/>                                                                                     |
| Header<br/>                   | <dl> <dt>IACom.h (also requires IACom\_i.c)</dt> </dl> |
| DLL<br/>                      | <dl> <dt>IACom.dll</dt> </dl>                          |



## See also

<dl> <dt>

[**IInkAnalysisRecognizer**](iinkanalysisrecognizer.md)
</dt> <dt>

[Ink Analysis Reference](ink-analysis-reference.md)
</dt> </dl>

�

�



