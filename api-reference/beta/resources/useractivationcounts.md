---
title: "userActivationCounts resource type"
description: "The following is a JSON representation of the resource."
author: "dkershaw10"
localization_priority: Normal
ms.prod: "microsoft-identity-platform"
---

# userActivationCounts resource type

## Properties

| Property          | Type   | Description                              |
| :---------------- | :----- | ---------------------------------------- |
| productType       | String | The product type, such as "Office 365 ProPlus", "Project Client", or "Visio Pro for Office 365". |
| lastActivatedDate | Date   | The date of the latest activation.       |
| windows           | Int64  | The activation count on Windows. This number includes every activation on any Windows computer. |
| mac               | Int64  | The activation count on Mac OS.          |
| windows10Mobile   | Int64  | The activation count on Windows 10 mobile. |
| ios               | Int64  | The activation count on iOS.             |
| android           | Int64  | The activation count on an Android device.  |
| activatedOnSharedComputer   | Boolean | True if the user used the product on a shared computer before. |

## JSON representation

The following is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "@odata.type": "microsoft.graph.userActivationCounts"
} -->

```json
{
  "productType": "String", 
  "lastActivatedDate": "Date", 
  "windows": 1024, 
  "mac": 1024, 
  "windows10Mobile": 1024, 
  "ios": 1024, 
  "android": 1024,
  "activatedOnSharedComputer": true 
}
```
