# Clan Tracking

This endpoint returns very basic data on whether a clan is included in the [Clan History Tracking](/endpoints/clan_history.md)

## HTTP Request

`GET http://api.cr-api.com/clan/<TAG>/tracking`

### URL Parameters

Parameter | Description
--- | ---
TAG | The clan tag of the clan to retrieve

## Response

### Included in the tracking
http://api.cr-api.com/clan/2CCCP/tracking

Below is the full JSON Response
```json
{
    "tag": "2CCCP",
    "active": true,
    "available": true,
    "snapshotCount": 218
}
```

### Not included in the tracking
https://api.cr-api.com/clan/28JU8P0Y/tracking

Below is the full JSON Response
```json
{
    "tag": "28JU8P0Y",
    "active": false,
    "available": false,
    "snapshotCount": 0
}
```