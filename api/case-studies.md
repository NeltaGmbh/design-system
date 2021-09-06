---
description: This endpoint allows you to get case studies that are published by Nelta
---

# Case Studies

{% api-method method="get" host="https://api.nelta.de" path="/case-studies" %}
{% api-method-summary %}
Get Case Studies
{% endapi-method-summary %}

{% api-method-description %}
This endpoint allows you to get case studies that are published by Nelta
{% endapi-method-description %}

{% api-method-spec %}
{% api-method-request %}
{% api-method-path-parameters %}
{% api-method-parameter name="slug" type="string" required=true %}
The slug path to the selected case study
{% endapi-method-parameter %}

{% api-method-parameter name="id" type="string" required=false %}
The ID of the case study to be retrieved
{% endapi-method-parameter %}
{% endapi-method-path-parameters %}

{% api-method-query-parameters %}
{% api-method-parameter name="client\_name" type="string" required=false %}
Gets the client name
{% endapi-method-parameter %}

{% api-method-parameter name="slogan" type="string" required=false %}
Gets the client slogan
{% endapi-method-parameter %}

{% api-method-parameter name="brief" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="solution" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="project\_description\_title" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="project\_description\_description" type="string" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="company\_presentation" type="object" required=false %}

{% endapi-method-parameter %}

{% api-method-parameter name="jobs\_dones" type="string" required=false %}
Retrieve an array of objects containing all jobs done to particular case study
{% endapi-method-parameter %}

{% api-method-parameter name="gallery" type="array" required=false %}

{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}

{% endapi-method-response-example-description %}

```

```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

