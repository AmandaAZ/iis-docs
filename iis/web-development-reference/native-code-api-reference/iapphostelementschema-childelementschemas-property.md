---
title: "IAppHostElementSchema::ChildElementSchemas Property | Microsoft Docs"
ms.custom: ""
ms.date: "10/07/2016"
ms.reviewer: ""
ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 5682845e-c5c1-4bf8-aaed-54c17c940214
caps.latest.revision: 7
author: "shirhatti"
manager: "wpickett"
---
# IAppHostElementSchema::ChildElementSchemas Property
Gets the schema used for child elements that are contained in the corresponding [IAppHostElement Interface](../../web-development-reference\webdev-native-api-reference/iapphostelement-interface.md) object.  
  
## Syntax  
  
```cpp  
[propget] HRESULT ChildElementSchemas(  
   [out,  
   retval] IAppHostElementSchemaCollection * ppChildSchemas  
);  
```  
  
#### Parameters  
 `ppChildSchemas`  
 Contains the schema collection of the supported child [IAppHostElement Interface](../../web-development-reference\webdev-native-api-reference/iapphostelement-interface.md) objects.  
  
## Return Value  
 An `HRESULT`. Possible values include, but are not limited to, those in the following table.  
  
|Value|Description|  
|-----------|-----------------|  
|S_OK|Indicates that the operation was successful.|  
  
## Requirements  
  
|Type|Description|  
|----------|-----------------|  
|Client|-   IIS 7.0 on [!INCLUDE[winvista](../../wmi-provider/includes/winvista-md.md)]<br />-   IIS 7.5 on Windows 7<br />-   IIS 8.0 on Windows 8<br />-   IIS 10.0 on Windows 10|  
|Server|-   IIS 7.0 on [!INCLUDE[winsrv2008](../../wmi-provider/includes/winsrv2008-md.md)]<br />-   IIS 7.5 on Windows Server 2008 R2<br />-   IIS 8.0 on Windows Server 2012<br />-   IIS 8.5 on Windows Server 2012 R2<br />-   IIS 10.0 on Windows Server 2016|  
|Product|-   IIS 7.0, IIS 7.5, IIS 8.0, IIS 8.5, IIS 10.0<br />-   [!INCLUDE[iisexp75](../../web-development-reference/native-code-api-reference/includes/iisexp75-md.md)], [!INCLUDE[iisexp80](../../web-development-reference/native-code-api-reference/includes/iisexp80-md.md)], [!INCLUDE[iisexp100](../../web-development-reference/native-code-api-reference/includes/iisexp100-md.md)]|  
|Header|Ahadmin.h|  
  
## See Also  
 [IAppHostElement Interface](../../web-development-reference\webdev-native-api-reference/iapphostelement-interface.md)   
 [IAppHostElementSchema Interface](../../web-development-reference\webdev-native-api-reference/iapphostelementschema-interface.md)   
 [IAppHostElementSchemaCollection Interface](../../web-development-reference\webdev-native-api-reference/iapphostelementschemacollection-interface.md)