---
title: "Record.ChangeCompany([String]) Method"
description: "Redirects references to table data from one company to another."
ms.author: solsen
ms.custom: na
ms.date: 07/07/2021
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: reference
ms.service: "dynamics365-business-central"
author: SusanneWindfeldPedersen
---
[//]: # (START>DO_NOT_EDIT)
[//]: # (IMPORTANT:Do not edit any of the content between here and the END>DO_NOT_EDIT.)
[//]: # (Any modifications should be made in the .xml files in the ModernDev repo.)
# Record.ChangeCompany([String]) Method
> **Version**: _Available or changed with runtime version 1.0._

Redirects references to table data from one company to another.


## Syntax
```AL
[Ok := ]  Record.ChangeCompany([CompanyName: String])
```
## Parameters
*Record*  
&emsp;Type: [Record](record-data-type.md)  
An instance of the [Record](record-data-type.md) data type.  

*[Optional] CompanyName*  
&emsp;Type: [String](../string/string-data-type.md)  
The name of the company to which you want to change. If you omit this parameter, you change back to the current company.
          


## Return Value
*[Optional] Ok*  
&emsp;Type: [Boolean](../boolean/boolean-data-type.md)  
**true** if the operation was successful; otherwise **false**.   If you omit this optional return value and the operation does not execute successfully, a runtime error will occur.  


[//]: # (IMPORTANT: END>DO_NOT_EDIT)
## See Also
[Record Data Type](record-data-type.md)  
[Getting Started with AL](../../devenv-get-started.md)  
[Developing Extensions](../../devenv-dev-overview.md)