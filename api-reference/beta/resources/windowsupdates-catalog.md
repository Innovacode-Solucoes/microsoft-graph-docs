---
title: "catalog resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# catalog resource type

Namespace: microsoft.graph.windowsUpdates

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

The catalog of content that can be approved for deployment.

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List entries](../api/windowsupdates-catalog-list-entries.md)|[catalogEntry](../resources/windowsupdates-catalogentry.md) collection|Get the catalogEntry resources from the entries navigation property.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|An identifier for the catalog. Read-only.|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|entries|[catalogEntry](../resources/windowsupdates-catalogentry.md) collection|Lists the content that can be approved for deployment. Read-only.|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.windowsUpdates.catalog",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.windowsUpdates.catalog",
  "id": "String (identifier)"
}
```
