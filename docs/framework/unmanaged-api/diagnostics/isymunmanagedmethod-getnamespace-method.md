---
title: "ISymUnmanagedMethod::GetNamespace Method | Microsoft Docs"
ms.custom: ""
ms.date: "03/30/2017"
ms.prod: ".net-framework"
ms.reviewer: ""
ms.suite: ""
ms.technology: 
  - "dotnet-clr"
ms.tgt_pltfrm: ""
ms.topic: "reference"
apiname: 
  - "ISymUnmanagedMethod.GetNamespace"
apilocation: 
  - "diasymreader.dll"
apitype: "COM"
f1_keywords: 
  - "ISymUnmanagedMethod::GetNamespace"
dev_langs: 
  - "C++"
helpviewer_keywords: 
  - "ISymUnmanagedMethod::GetNamespace method [.NET Framework debugging]"
  - "GetNamespace method [.NET Framework debugging]"
ms.assetid: 7fbbac42-b966-406d-9ae9-67bf3aea74ce
caps.latest.revision: 8
author: "mairaw"
ms.author: "mairaw"
manager: "wpickett"
---
# ISymUnmanagedMethod::GetNamespace Method
Gets the namespace within which this method is defined.  
  
## Syntax  
  
```  
HRESULT GetNamespace(  
   [out] ISymUnmanagedNamespace  **pRetVal);  
```  
  
#### Parameters  
 `pRetVal`  
 [out] A pointer that is set to the returned [ISymUnmanagedNamespace](../../../../docs/framework/unmanaged-api/diagnostics/isymunmanagednamespace-interface.md) interface.  
  
## Return Value  
 S_OK if the method succeeds; otherwise, E_FAIL or some other error code.  
  
## Requirements  
 **Header:** CorSym.idl, CorSym.h  
  
## See Also  
 [ISymUnmanagedMethod Interface](../../../../docs/framework/unmanaged-api/diagnostics/isymunmanagedmethod-interface.md)