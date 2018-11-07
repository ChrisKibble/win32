---
Description: Requests to get specified information from the object table for the specified event.
MS-HAID: vspixengine.IObjectTableRequest\_RequestAsync\_DWORD\_DWORD\_DWORD\_arr\_IObjectTableCallback\_ptr\_DWORD\_DWORD
MSHAttr:
- PreferredSiteName:MSDN
- PreferredLib:/library/windows/desktop
title: IObjectTableRequest::RequestAsync method
ms.topic: article
ms.date: 05/31/2018
---

# <span id="vspixengine.iobjecttablerequest_requestasync_dword_dword_dword_arr_iobjecttablecallback_ptr_dword_dword"></span>IObjectTableRequest::RequestAsync method

Requests to get specified information from the object table for the specified event.

## Syntax


```C++
);
```

## Parameters

*eventID*   
The specified event.

*numColumns*   
The number of columns (fields) of information to get.

*count1\_columns*   
The specified columns (fields).

*requestCallback*   
The address of callback used to notify the host of results.

*requestCookie*   
A cookie that uniquely identifies the request, and can be used to signal for it to be cancelled.

*progressIntervalMsecs*   
Not used.

## Return value

If this method succeeds, it returns **S\_OK**. Otherwise, it returns an **HRESULT** error code.

## Requirements

<table><colgroup><col style="width: 50%" /><col style="width: 50%" /></colgroup><tbody><tr class="odd"><td><p>Header</p></td><td>Vspixengine.h</td></tr></tbody></table>

## <span id="see_also"></span>See also

[**IObjectTableRequest**](https://msdn.microsoft.com/library/windows/desktop/mt422699)

 

 


