# Delete calendarGroup

Delete a calendar group.
### Prerequisites
One of the following **scopes** is required to execute this API: 
*Calendars.ReadWrite*
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
DELETE /me/calendarGroup
DELETE /users/<id>/calendarGroup
DELETE /users/<userPrincipalName>/calendarGroup
DELETE /me/calendarGroups/<id>
DELETE /users/<id>/calendarGroups/<id>
DELETE /users/<userPrincipalName>/calendarGroups/<id>
```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| Authorization  | string  | Bearer <token>. Required. |

### Request body
Do not supply a request body for this method.


### Response
If successful, this method returns `204, No Content` response code. It does not return anything in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "delete_calendargroup"
}-->
```http
DELETE https://graph.microsoft.com/v1.0/me/calendarGroups/<id>
```
##### Response
Here is an example of the response. Note: The response object shown here may be truncated for brevity. All of the properties will be returned from an actual call.
<!-- {
  "blockType": "response",
  "truncated": true
} -->
```http
Status code: 204
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Delete calendarGroup",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->
