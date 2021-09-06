---
description: This endpoint allow you to get clients that are published by Nelta
---

# Clients

{% api-method method="get" host="https://api.nelta.de" path="/clients" %}
{% api-method-summary %}
Get Clients
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get clients array of objects.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="slug" type="string" required=true %}
The slug of client to be retrived
{% endapi-method-parameter %}

{% api-method-parameter name="id" type="string" required=false %}
ID of the client to be retrived
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-query-parameters %}
{% api-method-parameter name="company\_name" type="string" %}
Filter clients by company name
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Client successfully retrieved.
{% endapi-method-response-example-description %}

```javascript
{
    "_id": "61327511fb9e183ee8b1a10f",
    "company_name": "Airplus",
    "url": "https://www.airplus.com",
    "createdAt": "2021-09-03T19:18:41.057Z",
    "updatedAt": "2021-09-03T19:18:41.231Z",
    "__v": 0,
    "logo": {
        "_id": "6132750dfb9e183ee8b1a10e",
        "name": "AirPlus_International.svg",
        "alternativeText": "",
        "caption": "",
        "hash": "Air_Plus_International_b8bf68ecac",
        "ext": ".svg",
        "mime": "image/svg+xml",
        "size": 5.73,
        "url": "/uploads/Air_Plus_International_b8bf68ecac.svg",
        "provider": "local",
        "width": 122,
        "height": 38,
        "related": [
            "61327511fb9e183ee8b1a10f"
        ],
        "createdAt": "2021-09-03T19:18:37.594Z",
        "updatedAt": "2021-09-03T21:29:07.768Z",
        "__v": 0,
        "formats": {},
        "id": "6132750dfb9e183ee8b1a10e"
    },
    "id": "61327511fb9e183ee8b1a10f"
}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=400 %}
{% api-method-response-example-description %}
When a bad request happens
{% endapi-method-response-example-description %}

```javascript
{
    "statusCode": 400,
    "error": "Bad Request",
    "message": "Your filters contain a field '_v' that doesn't appear on your model definition nor its relations"
}
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=404 %}
{% api-method-response-example-description %}
Could not find a client matching this query.
{% endapi-method-response-example-description %}

```
[]
```
{% endapi-method-response-example %}

{% api-method-response-example httpCode=503 %}
{% api-method-response-example-description %}
Bad response or internal server error
{% endapi-method-response-example-description %}

```javascript
{
    "statusCode": 500,
    "error": "Internal Server Error",
    "message": "An internal server error occurred"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}



