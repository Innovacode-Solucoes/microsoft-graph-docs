---
title: "Add identityProvider"
description: "Add identityProviders by posting to the identityProviders collection."
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: apiPageType
---

# Add identityProvider
Namespace: microsoft.graph



Add identityProviders by posting to the identityProviders collection.

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
POST /identity/b2xUserFlows/{b2xIdentityUserFlowId}/identityProviders/$ref
```

## Request headers
|Name|Description|
|:---|:---|
|Authorization|Bearer {token}. Required.|
|Content-Type|application/json. Required.|

## Request body
In the request body, supply a JSON representation of the [identityProvider](../resources/identityprovider.md) object.

The following table shows the properties that are required when you create the [identityProvider](../resources/identityprovider.md).

|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md)|
|type|String|**TODO: Add Description**|
|name|String|**TODO: Add Description**|
|clientId|String|**TODO: Add Description**|
|clientSecret|String|**TODO: Add Description**|



## Response

If successful, this method returns a `204 No Content` response code and an [identityProvider](../resources/identityprovider.md) object in the response body.

## Examples

### Request
<!-- {
  "blockType": "request",
  "name": "create_identityprovider_from_identityproviders"
}
-->
``` http
POST https://graph.microsoft.com/v1.0/identity/b2xUserFlows/{b2xIdentityUserFlowId}/identityProviders/$ref
Content-Type: application/json
Content-length: 154

{
  "@odata.type": "#microsoft.graph.identityProvider",
  "type": "String",
  "name": "String",
  "clientId": "String",
  "clientSecret": "String"
}
```


### Response
**Note:** The response object shown here might be shortened for readability.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.identityProvider"
}
-->
``` http
HTTP/1.1 204 No Content
Content-Type: application/json

{
  "@odata.type": "#microsoft.graph.identityProvider",
  "id": "4ca9a91b-a91b-4ca9-1ba9-a94c1ba9a94c",
  "type": "String",
  "name": "String",
  "clientId": "String",
  "clientSecret": "String"
}
```
