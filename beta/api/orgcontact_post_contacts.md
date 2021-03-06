# Create OrgContact

Use this API to create a new OrgContact.
### Prerequisites
The following **scopes** are required to execute this API: 
### HTTP request
<!-- { "blockType": "ignored" } -->
```http
POST /buckets

```
### Request headers
| Name       | Type | Description|
|:---------------|:--------|:----------|
| Authorization  | string  | Bearer <token>. Required. |

### Request body
In the request body, supply a JSON representation of [OrgContact](../resources/orgcontact.md) object.


### Response
If successful, this method returns `201, Created` response code and [OrgContact](../resources/orgcontact.md) object in the response body.

### Example
##### Request
Here is an example of the request.
<!-- {
  "blockType": "request",
  "name": "create_orgcontact_from_contacts"
}-->
```http
POST https://graph.microsoft.com/beta/contacts
Content-type: application/json
Content-length: 260

{
  "orgContact": {
    "businessPhones": [
      "businessPhones-value"
    ],
    "city": "city-value",
    "companyName": "companyName-value",
    "country": "country-value",
    "department": "department-value",
    "displayName": "displayName-value"
  }
}
```
In the request body, supply a JSON representation of [orgContact](../resources/orgcontact.md) object.
##### Response
Here is an example of the response. Note: The response object shown here may be truncated for brevity. All of the properties will be returned from an actual call.
<!-- {
  "blockType": "response",
  "truncated": true,
  "@odata.type": "microsoft.graph.orgcontact"
} -->
```http
Content-type: application/json
Content-length: 260

{
  "orgContact": {
    "businessPhones": [
      "businessPhones-value"
    ],
    "city": "city-value",
    "companyName": "companyName-value",
    "country": "country-value",
    "department": "department-value",
    "displayName": "displayName-value"
  }
}
```

<!-- uuid: 8fcb5dbc-d5aa-4681-8e31-b001d5168d79
2015-10-25 14:57:30 UTC -->
<!-- {
  "type": "#page.annotation",
  "description": "Create OrgContact",
  "keywords": "",
  "section": "documentation",
  "tocPath": ""
}-->