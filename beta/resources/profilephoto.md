# profilePhoto resource type



### JSON representation

Here is a JSON representation of the resource.

<!-- {
  "blockType": "resource",
  "optionalProperties": [

  ],
  "@odata.type": "microsoft.graph.profilephoto"
}-->

```json
{
  "id": "240X240",
  "height": 240,
  "width": 240
}

```
### Properties
| Property	   | Type	|Description|
|:---------------|:--------|:----------|
|id|string|Read-only.|
|height|int32|The height of the photo. Read-only.|
|width|int32|The width of the photo. Read-only.|

### Relationships
None


### Methods

| Method		   | Return Type	|Description|
|:---------------|:--------|:----------|
|[Get profilePhoto](../api/profilephoto_get.md) | [profilePhoto](profilephoto.md) |Read the photo and properties of **profilePhoto**. |
|[Update](../api/profilephoto_update.md) | [profilePhoto](profilephoto.md)  |Update the photo. |

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "profilePhoto resource",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->