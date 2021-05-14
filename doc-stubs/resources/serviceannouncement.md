---
title: "serviceAnnouncement resource type"
description: "**TODO: Add Description**"
author: "**TODO: Provide Github Name. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
localization_priority: Normal
ms.prod: "**TODO: Add MS prod. See [topic-level metadata reference](https://msgo.azurewebsites.net/add/document/guidelines/metadata.html#topic-level-metadata)**"
doc_type: resourcePageType
---

# serviceAnnouncement resource type

Namespace: microsoft.graph

[!INCLUDE [beta-disclaimer](../../includes/beta-disclaimer.md)]

**TODO: Add Description**


Inherits from [entity](../resources/entity.md).

## Methods
|Method|Return type|Description|
|:---|:---|:---|
|[List serviceAnnouncements](../api/serviceannouncement-list.md)|[serviceAnnouncement](../resources/serviceannouncement.md) collection|Get a list of the [serviceAnnouncement](../resources/serviceannouncement.md) objects and their properties.|
|[Create serviceAnnouncement](../api/serviceannouncement-create.md)|[serviceAnnouncement](../resources/serviceannouncement.md)|Create a new [serviceAnnouncement](../resources/serviceannouncement.md) object.|
|[Get serviceAnnouncement](../api/serviceannouncement-get.md)|[serviceAnnouncement](../resources/serviceannouncement.md)|Read the properties and relationships of a [serviceAnnouncement](../resources/serviceannouncement.md) object.|
|[Update serviceAnnouncement](../api/serviceannouncement-update.md)|[serviceAnnouncement](../resources/serviceannouncement.md)|Update the properties of a [serviceAnnouncement](../resources/serviceannouncement.md) object.|
|[Delete serviceAnnouncement](../api/serviceannouncement-delete.md)|None|Deletes a [serviceAnnouncement](../resources/serviceannouncement.md) object.|
|[List healthOverviews](../api/serviceannouncement-list-healthoverviews.md)|[serviceHealth](../resources/servicehealth.md) collection|Get the serviceHealth resources from the healthOverviews navigation property.|
|[Create serviceHealth](../api/serviceannouncement-post-healthoverviews.md)|[serviceHealth](../resources/servicehealth.md)|Create a new serviceHealth object.|
|[List issues](../api/serviceannouncement-list-issues.md)|[serviceHealthIssue](../resources/servicehealthissue.md) collection|Get the serviceHealthIssue resources from the issues navigation property.|
|[Create serviceHealthIssue](../api/serviceannouncement-post-issues.md)|[serviceHealthIssue](../resources/servicehealthissue.md)|Create a new serviceHealthIssue object.|
|[List messages](../api/serviceannouncement-list-messages.md)|[serviceUpdateMessage](../resources/serviceupdatemessage.md) collection|Get the serviceUpdateMessage resources from the messages navigation property.|
|[Create serviceUpdateMessage](../api/serviceannouncement-post-messages.md)|[serviceUpdateMessage](../resources/serviceupdatemessage.md)|Create a new serviceUpdateMessage object.|

## Properties
|Property|Type|Description|
|:---|:---|:---|
|id|String|**TODO: Add Description** Inherited from [entity](../resources/entity.md).|

## Relationships
|Relationship|Type|Description|
|:---|:---|:---|
|healthOverviews|[serviceHealth](../resources/servicehealth.md) collection|**TODO: Add Description**|
|issues|[serviceHealthIssue](../resources/servicehealthissue.md) collection|**TODO: Add Description**|
|messages|[serviceUpdateMessage](../resources/serviceupdatemessage.md) collection|**TODO: Add Description**|

## JSON representation
The following is a JSON representation of the resource.
<!-- {
  "blockType": "resource",
  "keyProperty": "id",
  "@odata.type": "microsoft.graph.serviceAnnouncement",
  "baseType": "microsoft.graph.entity",
  "openType": false
}
-->
``` json
{
  "@odata.type": "#microsoft.graph.serviceAnnouncement",
  "id": "String (identifier)"
}
```
