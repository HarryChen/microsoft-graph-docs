---
title: "binaryManagementConditionExpression resource type"
description: "A management condition expression that is evaluated using a binary operation."
localization_priority: Normal
author: "tfitzmac"
ms.prod: "Intune"
---

# binaryManagementConditionExpression resource type

> **Important:** APIs under the /beta version in Microsoft Graph are subject to change. Use of these APIs in production applications is not supported.

> **Note:** The Microsoft Graph API for Intune requires an [active Intune license](https://go.microsoft.com/fwlink/?linkid=839381) for the tenant.

A management condition expression that is evaluated using a binary operation.


Inherits from [managementConditionExpressionModel](../resources/intune-fencing-managementconditionexpressionmodel.md)

## Properties
|Property|Type|Description|
|:---|:---|:---|
|operator|[binaryManagementConditionExpressionOperatorType](../resources/intune-fencing-binarymanagementconditionexpressionoperatortype.md)|The operator used in the evaluation of the binary operation. Possible values are: `or`, `and`.|
|firstOperand|[managementConditionExpressionModel](../resources/intune-fencing-managementconditionexpressionmodel.md)|The first operand of the binary operation.|
|secondOperand|[managementConditionExpressionModel](../resources/intune-fencing-managementconditionexpressionmodel.md)|The second operand of the binary operation.|

## Relationships
None

## JSON Representation
Here is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.binaryManagementConditionExpression"
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.binaryManagementConditionExpression",
  "operator": "String",
  "firstOperand": {
    "@odata.type": "microsoft.graph.managementConditionExpressionModel"
  },
  "secondOperand": {
    "@odata.type": "microsoft.graph.managementConditionExpressionModel"
  }
}
```




