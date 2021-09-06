---
description: This endpoint allows you to get general settings from Nelta
---

# General Settings

{% api-method method="get" host="https://api.nelta.de" path="/general-settings" %}
{% api-method-summary %}
Get General Settings
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get general settings from Nelta
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-query-parameters %}
{% api-method-parameter name="working\_hours" type="string" required=false %}
Working hours of the company
{% endapi-method-parameter %}

{% api-method-parameter name="footer\_copyright" type="string" required=false %}
Footer copyright paragraph
{% endapi-method-parameter %}

{% api-method-parameter name="xing" type="string" required=false %}
XING URL
{% endapi-method-parameter %}

{% api-method-parameter name="twitter" type="string" required=false %}
Twitter URL
{% endapi-method-parameter %}

{% api-method-parameter name="linkedin" type="string" required=false %}
Linkedin URL
{% endapi-method-parameter %}

{% api-method-parameter name="email\_address" type="string" required=false %}
Nelta's email address
{% endapi-method-parameter %}

{% api-method-parameter name="phone\_number" type="string" required=false %}
Nelta's phone number
{% endapi-method-parameter %}

{% api-method-parameter name="address" type="string" required=false %}
Office address
{% endapi-method-parameter %}

{% api-method-parameter name="footer\_links" type="array" required=false %}
Links to be added to the footer section with title and url
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
General settings successfully retrieved
{% endapi-method-response-example-description %}

```javascript
{
    "_id": "6135fe20bd7e92045c1364f6",
    "working_hours": "Mo - Sa 8.00 - 18.00",
    "footer_copyright": "Copyright © 2020 - 2021 Nelta. All Rights Reserved.",
    "xing": "https://www.xing.com/companies/nelta",
    "email_address": "contact@nelta.de",
    "twitter": "https://twitter.com/NeltaGmbh",
    "address": "Harvestehuder Weg 43, 20149 Hamburg",
    "phone_number": "040 - 3694 0339",
    "linkedin": "https://www.linkedin.com/company/nelta-magnified-efficieny/",
    "footer_links": [
        {
            "_id": "6135fe20bd7e92045c1364f7",
            "title": "Impressum",
            "link": "#",
            "__v": 0,
            "id": "6135fe20bd7e92045c1364f7"
        },
        {
            "_id": "6135fe20bd7e92045c1364f8",
            "title": "Datenschutzerklärung",
            "link": "#",
            "__v": 0,
            "id": "6135fe20bd7e92045c1364f8"
        },
        {
            "_id": "6135fe20bd7e92045c1364f9",
            "title": "AGB",
            "link": "#",
            "__v": 0,
            "id": "6135fe20bd7e92045c1364f9"
        }
    ],
    "createdAt": "2021-09-06T11:40:16.890Z",
    "updatedAt": "2021-09-06T11:40:17.269Z",
    "__v": 1,
    "id": "6135fe20bd7e92045c1364f6"
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
Could not find any settings matching this query
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

