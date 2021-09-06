---
description: This endpoint allows you to get jobs that are published by Nelta
---

# Jobs

{% api-method method="get" host="https://api.nelta.de" path="/jobs" %}
{% api-method-summary %}
Get Jobs
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get jobs that are published by Nelta
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="slug" type="string" required=true %}
The slug path to the selected job
{% endapi-method-parameter %}

{% api-method-parameter name="id" type="string" required=false %}
The ID of the job to be retrieved
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Job successfully retrieved
{% endapi-method-response-example-description %}

```javascript
{
    "job_time": "FullTime",
    "Location": "Office",
    "_id": "61327708fb9e183ee8b1a11c",
    "title": "IT Recruiter (m/w/d)",
    "published_at": "2021-09-03T19:27:16.583Z",
    "title_content": [
        {
            "_id": "61327708fb9e183ee8b1a11d",
            "title": "Stellenbeschreibung",
            "content": "Nelta ist ein agiles IT-Beratungshaus mit Hauptniederlassung in Hamburg-Harvestehude. Wir bieten ein erstklassiges Leistungsportfolio, bestehend aus innovativen Lösungen, integrierten und ganzheitlichen Services, in den Bereichen QA, SAP, Software Development, sowie 1st und 2nd Level IT Support.\n\nUm weitere regionale als auch nationale Kundenprojekte zu realisieren, wird ab sofort ein/e Recruiter *in (m/w/d)in unbefristeter Festanstellung, in Teilzeit gesucht.",
            "__v": 0,
            "id": "61327708fb9e183ee8b1a11d"
        },
        {
            "_id": "61327708fb9e183ee8b1a11e",
            "title": "Was wir Dir bieten:",
            "content": "Ausgewogene Work-Life-Balance durch flexible Arbeitszeiten\nHome-Office & mobiles Arbeiten nach Bedarf\nFlache Hierarchien & kurze Entscheidungswege\nCoaching und Support durch systemische Coaches & Business Psychologen\nInvestition in Deine Zukunft durch IT-, Sprach- und Persönlichkeitstrainings & – Weiterbildungen\nViel Raum für Eigeninitiative & Kreativität\nArbeiten aus einer Bürovilla mit Alsterblick\nEin optimales Onboarding\nEin wirklich durch & durch dynamisches & cooles Team",
            "__v": 0,
            "id": "61327708fb9e183ee8b1a11e"
        },
        {
            "_id": "61327708fb9e183ee8b1a11f",
            "title": "Folgende Aufgaben erwarten dich:",
            "content": "Gemeinsamer Ausbau der Recruiting Prozesse, zusammen mit dem HR Management\nDefinition, Gestaltung und Umsetzung der Suchstrategien\nActive Sourcing, wie z.B. in den sozialen Medien wie LinkedIn, Xing, etc. Dies beinhaltet auch das aktive Anschreiben bei Xing und Linkedin nach bestimmten Vorgaben und Abläufen\nÜberwachung der Qualität und regelmäßige Reports an das HR Management\nPflege und Aktualisierung des Bewerberpools",
            "__v": 0,
            "id": "61327708fb9e183ee8b1a11f"
        },
        {
            "_id": "61327708fb9e183ee8b1a120",
            "title": "Das bringst Du mit:",
            "content": "Wir werden dir nicht vorgeben, ob oder was du studiert haben solltest – Du musst uns einfach überzeugen, dass du die richtige Person für die Position bist\nErste Erfahrungen im Recruiting sind wünschenswert (idealerweise im active sourcing), aber nicht zwingend erforderlich\nDu arbeitest selbstständig und eigeninitiativ, das bedeutet viel Freiheit und gleichzeitig auch große Verantwortung\nDu bist flexibel und belastbar\nDu hast eine hands-on Mentalität\nDu bist offen für neue Prozesse und agile Arbeitsweisen\nGute Englisch Kenntnisse",
            "__v": 0,
            "id": "61327708fb9e183ee8b1a120"
        }
    ],
    "job_overview": {
        "Vertragsart": "Unbefristet",
        "Karrierelevel": "Consultant",
        "Qualifikation": "Bachelor",
        "_id": "61327709fb9e183ee8b1a125",
        "Veroffentlicht_am": "2021-09-03",
        "Erfahrung": 3,
        "__v": 0,
        "id": "61327709fb9e183ee8b1a125"
    },
    "createdAt": "2021-09-03T19:27:04.737Z",
    "updatedAt": "2021-09-03T19:27:16.778Z",
    "__v": 2,
    "id": "61327708fb9e183ee8b1a11c"
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
Could not find any job matching this query
{% endapi-method-response-example-description %}

```javascript
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

