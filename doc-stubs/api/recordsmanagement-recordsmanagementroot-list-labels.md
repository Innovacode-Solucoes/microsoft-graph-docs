---
title: "List labels"
description: "Get the retentionLabel resources from the labels navigation property."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
ms.localizationpriority: medium
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# List labels
Namespace: microsoft.graph.recordsManagement

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

Get the retentionLabel resources from the labels navigation property.

## Permissions
One of the following permissions is required to call this API. To learn more, including how to choose permissions, see [Permissions](/graph/permissions-reference).

|Permission type|Permissions (from least to most privileged)|
|:---|:---|
|Delegated (work or school account)|**TODO: Provide applicable permissions.**|
|Delegated (personal Microsoft account)|**TODO: Provide applicable permissions.**|
|Application|**TODO: Provide applicable permissions.**|

## HTTP request

<!-- {
  "blockType": "ignored"
}
-->
``` http
GET /compliance/recordsManagement/labels
```

## Optional query parameters
This method supports some of the OData query parameters to help customize the response. For general information, see [OData query parameters](/graph/query-parameters).

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|

## Request body
Do not supply a request body for this method.

## Response

If successful, this method returns a `200 OK` response code and a collection of [retentionLabel](../resources/retentionlabel.md) objects in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "list_retentionlabel"
}
-->
``` http
GET https://graph.microsoft.com/beta/compliance/recordsManagement/labels
```


### Response
>**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "Collection(microsoft.graph.recordsManagement.retentionLabel)"
}
-->
``` http
HTTP/1.1 200 OK
Content-Type: application/json

{
  "value": [
    {
      "@odata.type": "#microsoft.graph.recordsManagement.retentionLabel",
      "id": "6fb1c04e-c04e-6fb1-4ec0-b16f4ec0b16f",
      "displayName": "String",
      "behaviorDuringRetentionPeriod": "String",
      "actionAfterRetentionPeriod": "String",
      "retentionTrigger": "String",
      "retentionDurationInDays": "Integer",
      "isInUse": "Boolean",
      "descriptionForAdmins": "String",
      "descriptionForUsers": "String",
      "createdBy": {
        "@odata.type": "microsoft.graph.identitySet"
      },
      "createdDateTime": "String (timestamp)",
      "lastModifiedBy": {
        "@odata.type": "microsoft.graph.identitySet"
      },
      "lastModifiedDateTime": "String (timestamp)",
      "dispositionReviewStages": [
        {
          "@odata.type": "microsoft.graph.recordsManagement.dispositionReviewStage"
        }
      ]
    }
  ]
}
```

