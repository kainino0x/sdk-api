---
UID: NF:thumbcache.ISharedBitmap.GetSize
title: ISharedBitmap::GetSize (thumbcache.h)
description: Retrieves the size of the bitmap contained in an ISharedBitmap object.helpviewer_keywords: ["GetSize","GetSize method [Windows Shell]","GetSize method [Windows Shell]","ISharedBitmap interface","ISharedBitmap interface [Windows Shell]","GetSize method","ISharedBitmap.GetSize","ISharedBitmap::GetSize","_shell__GetSize","shell.ISharedBitmap_GetSize","thumbcache/ISharedBitmap::GetSize"]
old-location: shell\ISharedBitmap_GetSize.htm
tech.root: shell
ms.assetid: 612fbb6d-2539-4055-9037-7e64ddced4e9
ms.date: 12/05/2018
ms.keywords: GetSize, GetSize method [Windows Shell], GetSize method [Windows Shell],ISharedBitmap interface, ISharedBitmap interface [Windows Shell],GetSize method, ISharedBitmap.GetSize, ISharedBitmap::GetSize, _shell__GetSize, shell.ISharedBitmap_GetSize, thumbcache/ISharedBitmap::GetSize
f1_keywords:
- thumbcache/ISharedBitmap.GetSize
dev_langs:
- c++
req.header: thumbcache.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: Thumbcache.idl
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Thumbcache.h
api_name:
- ISharedBitmap.GetSize
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ISharedBitmap::GetSize


## -description


Retrieves the size of the bitmap contained in an <a href="https://docs.microsoft.com/windows/desktop/api/thumbcache/nn-thumbcache-isharedbitmap">ISharedBitmap</a> object.


## -parameters




### -param pSize [out]

Type: <b><a href="https://docs.microsoft.com/previous-versions/dd145106(v=vs.85)">SIZE</a>*</b>

When this method returns, contains a pointer to a value that specifies the size, in pixels, of the contained bitmap.


## -returns



Type: <b>HRESULT</b>

If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.



