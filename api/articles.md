---
description: This endpoint allows you to get articles that are published by Nelta
---

# Articles

{% api-method method="get" host="https://api.nelta.de" path="/articles" %}
{% api-method-summary %}
Get Articles
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get articles that are published by Nelta.
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="slug" type="string" required=true %}
The slug path to the selected article
{% endapi-method-parameter %}

{% api-method-parameter name="id" type="string" %}
The ID of the article to be retrieved
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-query-parameters %}
{% api-method-parameter name="title" type="string" required=false %}
The article title
{% endapi-method-parameter %}

{% api-method-parameter name="content" type="string" required=false %}
The content of the selected article
{% endapi-method-parameter %}

{% api-method-parameter name="categories" type="array" %}
Categories attached to an article
{% endapi-method-parameter %}

{% api-method-parameter name="featured\_image" type="array" %}
Featured image includes full size image and other formats which includes thumbnail, large, medium and small
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Article successfully retrieved.
{% endapi-method-response-example-description %}

```javascript
{
    "categories": [
        {
        "_id": "613274dcfb9e183ee8b1a10c",
        "category_name": "Business",
        "createdAt": "2021-09-03T19:17:48.570Z",
        "updatedAt": "2021-09-03T19:17:48.709Z",
        "__v": 0,
        "id": "613274dcfb9e183ee8b1a10c"
        },
        {
        "_id": "613274e3fb9e183ee8b1a10d",
        "category_name": "News",
        "createdAt": "2021-09-03T19:17:55.929Z",
        "updatedAt": "2021-09-03T19:17:56.073Z",
        "__v": 0,
        "id": "613274e3fb9e183ee8b1a10d"
        }
    ],
    "_id": "61327840fb9e183ee8b1a13c",
    "title": "Mitglied bei der BDU",
    "content": "Mit großem Stolz, dürfen wir bekanntgeben, dass wir nun mit dem Young Consultancy Status der BDU, wieder einen kleinen Schritt auf unserem Weg in die Welt der großen Player gemacht haben. \n\nDer Status „Young Consultancy“, welcher ein Angebot der BDU Servicegesellschaft für Unternehmensberater mbH für frisch gegründete oder junge Unternehmens- und Personalberatungen ist, steht uns deshalb nur solange zur Verfügung, wie die Mitgliedschaftsvoraussetzungen (fünf Jahre Berufserfahrung, davon drei Jahre Selbstständigkeit oder Führungsverantwortung als Unternehmensberater) noch nicht erfüllt wurden. Anschließend wird der Wechsel in die Mitgliedschaft im Branchenverband erfolgen. \n\n## Was bietet die Young Consultancy Mitgliedschaft?\n\nGerade in den ersten Jahren unserer jungen Unternehmensberatung, bekommen wir durch die BDU viele Orientierungshilfen um vorausschauend von den Fehlern anderer Firmen zu lernen und von den Tipps und Tricks zu profitieren. \n\nNeben Weiterbildungsmöglichkeiten für unsere Berater und Zugriffe auf Marktstudien “Facts&Figures”, erhalten wir regelmäßige Informationen aus der Branche und einen Plattform zum Brancheninternen austauschen. \n\nWir werden diese Mitgliedschaft nutzen, um von etwaigen Kooperationspartnern zu profitieren und unseren Horizont in der großen Beraterwelt stetig zu erweitern. So sehen wir die Mitgliedschaft nicht lediglich als interne Möglichkeit uns zu verbessern, sondern auch als besondere Bereicherung für unsere Kunden.",
    "published_at": "2021-09-03T19:32:19.136Z",
    "createdAt": "2021-09-03T19:32:16.474Z",
    "updatedAt": "2021-09-03T19:32:19.327Z",
    "__v": 0,
    "featured_image": {
        "_id": "6132783dfb9e183ee8b1a13b",
        "name": "executive_assessment_partnership_1160x650_1_1_9714f96bd8.jpg",
        "alternativeText": "",
        "caption": "",
        "hash": "executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9",
        "ext": ".jpg",
        "mime": "image/jpeg",
        "size": 58.29,
        "width": 1160,
        "height": 650,
        "url": "/uploads/executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9.jpg",
        "formats": {
            "thumbnail": {
                "name": "thumbnail_executive_assessment_partnership_1160x650_1_1_9714f96bd8.jpg",
                "hash": "thumbnail_executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 245,
                "height": 137,
                "size": 6.13,
                "path": null,
                "url": "/uploads/thumbnail_executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9.jpg"
            },
            "large": {
                "name": "large_executive_assessment_partnership_1160x650_1_1_9714f96bd8.jpg",
                "hash": "large_executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 1000,
                "height": 560,
                "size": 44.85,
                "path": null,
                "url": "/uploads/large_executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9.jpg"
            },
            "medium": {
                "name": "medium_executive_assessment_partnership_1160x650_1_1_9714f96bd8.jpg",
                "hash": "medium_executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 750,
                "height": 420,
                "size": 28.65,
                "path": null,
                "url": "/uploads/medium_executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9.jpg"
            },
            "small": {
                "name": "small_executive_assessment_partnership_1160x650_1_1_9714f96bd8.jpg",
                "hash": "small_executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 500,
                "height": 280,
                "size": 15.68,
                "path": null,
                "url": "/uploads/small_executive_assessment_partnership_1160x650_1_1_9714f96bd8_c47de637c9.jpg"
            }
        },
        "provider": "local",
        "related": [
            "61327840fb9e183ee8b1a13c"
        ],
        "createdAt": "2021-09-03T19:32:13.566Z",
        "updatedAt": "2021-09-03T21:28:54.837Z",
        "__v": 0,
        "id": "6132783dfb9e183ee8b1a13b"
    },
    "id": "61327840fb9e183ee8b1a13c"
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
Could not find any article matching this query.
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



