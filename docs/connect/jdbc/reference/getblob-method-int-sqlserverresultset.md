---
title: "getBlob Method (int) (SQLServerResultSet)"
description: "getBlob Method (int) (SQLServerResultSet)"
author: David-Engel
ms.author: davidengel
ms.date: "01/19/2017"
ms.service: sql
ms.subservice: connectivity
ms.topic: reference
apilocation: "sqljdbc.jar"
apiname: "SQLServerResultSet.getBlob (int)"
apitype: "Assembly"
---
# getBlob Method (int) (SQLServerResultSet)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

  Retrieves the value of the designated column index in the current row of this [SQLServerResultSet](../../../connect/jdbc/reference/sqlserverresultset-class.md) object as a Blob object in the Java programming language.  
  
## Syntax  
  
```  
  
public java.sql.Blob getBlob(int i)  
```  
  
#### Parameters  
 *i*  
  
 An **int** that indicates the column index.  
  
## Return Value  
 A Blob object.  
  
## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
  
## Remarks  
 This getBlob method is specified by the getBlob method in the java.sql.ResultSet interface.  
  
## See Also  
 [getBlob Method &#40;SQLServerResultSet&#41;](../../../connect/jdbc/reference/getblob-method-sqlserverresultset.md)   
 [SQLServerResultSet Members](../../../connect/jdbc/reference/sqlserverresultset-members.md)   
 [SQLServerResultSet Class](../../../connect/jdbc/reference/sqlserverresultset-class.md)  
  
  
