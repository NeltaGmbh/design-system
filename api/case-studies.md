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
A brief of the problem
{% endapi-method-parameter %}

{% api-method-parameter name="solution" type="string" required=false %}
The solution provided for the company
{% endapi-method-parameter %}

{% api-method-parameter name="project\_description\_title" type="string" required=false %}
A short title about the case study description
{% endapi-method-parameter %}

{% api-method-parameter name="project\_description\_description" type="string" required=false %}
A longer description of the case study
{% endapi-method-parameter %}

{% api-method-parameter name="company\_presentation" type="object" required=false %}
A PDF file to be downloaded for the case study
{% endapi-method-parameter %}

{% api-method-parameter name="jobs\_dones" type="string" required=false %}
Retrieve an array of objects containing all jobs done to a particular case study
{% endapi-method-parameter %}

{% api-method-parameter name="gallery" type="array" required=false %}
Retrieve an array of objects containing gallery images with its formats for the particular case study
{% endapi-method-parameter %}
{% endapi-method-query-parameters %}
{% endapi-method-request %}

{% api-method-response %}
{% api-method-response-example httpCode=200 %}
{% api-method-response-example-description %}
Case study successfully retrieved
{% endapi-method-response-example-description %}

```javascript
{
    "gallery": [
        {
            "_id": "613277d5fb9e183ee8b1a134",
            "name": "arlington-research-kN_kViDchA0-unsplash.jpg",
            "alternativeText": "",
            "caption": "",
            "hash": "arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b",
            "ext": ".jpg",
            "mime": "image/jpeg",
            "size": 693.14,
            "width": 3000,
            "height": 2002,
            "url": "/uploads/arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b.jpg",
            "formats": {
                "thumbnail": {
                "name": "thumbnail_arlington-research-kN_kViDchA0-unsplash.jpg",
                "hash": "thumbnail_arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 234,
                "height": 156,
                "size": 9.39,
                "path": null,
                "url": "/uploads/thumbnail_arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b.jpg"
                },
                "large": {
                "name": "large_arlington-research-kN_kViDchA0-unsplash.jpg",
                "hash": "large_arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 1000,
                "height": 667,
                "size": 98.37,
                "path": null,
                "url": "/uploads/large_arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b.jpg"
                },
                "medium": {
                "name": "medium_arlington-research-kN_kViDchA0-unsplash.jpg",
                "hash": "medium_arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 750,
                "height": 501,
                "size": 61.45,
                "path": null,
                "url": "/uploads/medium_arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b.jpg"
                },
                "small": {
                "name": "small_arlington-research-kN_kViDchA0-unsplash.jpg",
                "hash": "small_arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 500,
                "height": 334,
                "size": 32.43,
                "path": null,
                "url": "/uploads/small_arlington_research_k_N_k_Vi_Dch_A0_unsplash_57c177962b.jpg"
                }
            },
            "provider": "local",
            "related": [
                "613277fcfb9e183ee8b1a137"
            ],
            "createdAt": "2021-09-03T19:30:29.904Z",
            "updatedAt": "2021-09-03T21:28:32.265Z",
            "__v": 0,
            "id": "613277d5fb9e183ee8b1a134"    
        },
        {
            "_id": "613277d5fb9e183ee8b1a135",
            "name": "fran-innocenti-HRfvMO9I69U-unsplash.jpg",
            "alternativeText": "",
            "caption": "",
            "hash": "fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1",
            "ext": ".jpg",
            "mime": "image/jpeg",
            "size": 835.69,
            "width": 3496,
            "height": 2331,
            "url": "/uploads/fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1.jpg",
            "formats": {
                "thumbnail": {
                "name": "thumbnail_fran-innocenti-HRfvMO9I69U-unsplash.jpg",
                "hash": "thumbnail_fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 234,
                "height": 156,
                "size": 10.78,
                "path": null,
                "url": "/uploads/thumbnail_fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1.jpg"
                },
                "large": {
                "name": "large_fran-innocenti-HRfvMO9I69U-unsplash.jpg",
                "hash": "large_fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 1000,
                "height": 667,
                "size": 92.05,
                "path": null,
                "url": "/uploads/large_fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1.jpg"
                },
                "medium": {
                "name": "medium_fran-innocenti-HRfvMO9I69U-unsplash.jpg",
                "hash": "medium_fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 750,
                "height": 500,
                "size": 59.69,
                "path": null,
                "url": "/uploads/medium_fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1.jpg"
                },
                "small": {
                "name": "small_fran-innocenti-HRfvMO9I69U-unsplash.jpg",
                "hash": "small_fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1",
                "ext": ".jpg",
                "mime": "image/jpeg",
                "width": 500,
                "height": 333,
                "size": 33.52,
                "path": null,
                "url": "/uploads/small_fran_innocenti_H_Rfv_MO_9_I69_U_unsplash_f9bf8d1bc1.jpg"
                }
            },
            "provider": "local",
            "related": [
            "613277fcfb9e183ee8b1a137"
        ],
        "createdAt": "2021-09-03T19:30:29.930Z",
        "updatedAt": "2021-09-03T21:28:20.060Z",
        "__v": 0,
        "id": "613277d5fb9e183ee8b1a135"
        }
    ],
    "jobs_dones": [
        {
        "_id": "6132753ffb9e183ee8b1a114",
        "job_space": "Web Design",
        "createdAt": "2021-09-03T19:19:27.931Z",
        "updatedAt": "2021-09-03T19:19:28.074Z",
        "__v": 0,
        "id": "6132753ffb9e183ee8b1a114"
        },
        {
        "_id": "61327547fb9e183ee8b1a115",
        "job_space": "Web Development",
        "createdAt": "2021-09-03T19:19:35.437Z",
        "updatedAt": "2021-09-03T19:19:35.584Z",
        "__v": 0,
        "id": "61327547fb9e183ee8b1a115"
        },
        {
        "_id": "6132754cfb9e183ee8b1a116",
        "job_space": "Testing",
        "createdAt": "2021-09-03T19:19:40.104Z",
        "updatedAt": "2021-09-03T19:19:40.242Z",
        "__v": 0,
        "id": "6132754cfb9e183ee8b1a116"
        },
        {
        "_id": "61327553fb9e183ee8b1a117",
        "job_space": "Brand Consulting",
        "createdAt": "2021-09-03T19:19:47.672Z",
        "updatedAt": "2021-09-03T19:19:47.816Z",
        "__v": 0,
        "id": "61327553fb9e183ee8b1a117"
        },
        {
        "_id": "6132755bfb9e183ee8b1a118",
        "job_space": "Marketing Management",
        "createdAt": "2021-09-03T19:19:55.245Z",
        "updatedAt": "2021-09-03T19:19:55.404Z",
        "__v": 0,
        "id": "6132755bfb9e183ee8b1a118"
        },
        {
        "_id": "61327579fb9e183ee8b1a11a",
        "job_space": "Customer Insights",
        "createdAt": "2021-09-03T19:20:25.628Z",
        "updatedAt": "2021-09-03T19:20:25.781Z",
        "__v": 0,
        "id": "61327579fb9e183ee8b1a11a"
        }
    ],
    "_id": "613277fcfb9e183ee8b1a137",
    "project_description_title": "When walking alone in a jungle of true darkness, there are three things that can show you the way instinct to survive, the knowledge of navigation, creative imagination.",
    "project_description_description": "The diagnostic determined the stressors that affected sales and service levels. The team focused on resolving issues related to higher-than-normal back-orders and lead times, which stressed the entire supply chain and led to delays in medications reaching consumers.",
    "solution": "Our Trading helps clients run and transform their front, middle and back-office trading operations. We provide buy-side, sell-side and market infrastructure firms with a full-service offering, including systems integration and technology consulting services, to assist in delivering high performance trading and settlement. These apps run on a custom built blockchain",
    "brief": "The challenge is to bring a company whose web presence is boring up to date. The challenge is to ensure that when a client visits your website they feel positive about your company. The challenge is that most customers will judge you based on appearance alone, and if your website looks unprofessional or poorly made then they will think your company as a whole is unprofessional.",
    "slogan": "Magnified Efficiency",
    "client_name": "Nelta",
    "published_at": "2021-09-03T19:31:10.875Z",
    "createdAt": "2021-09-03T19:31:08.058Z",
    "updatedAt": "2021-09-03T19:31:11.083Z",
    "__v": 0,
    "company_presentation": {
        "_id": "613277e3fb9e183ee8b1a136",
        "name": "Argzon Haziraj - CV.pdf",
        "alternativeText": "",
        "caption": "",
        "hash": "Argzon_Haziraj_CV_0b02410d47",
        "ext": ".pdf",
        "mime": "application/pdf",
        "size": 1096.6,
        "url": "/uploads/Argzon_Haziraj_CV_0b02410d47.pdf",
        "provider": "local",
        "width": null,
        "height": null,
        "related": [
            "613277fcfb9e183ee8b1a137"
        ],
        "createdAt": "2021-09-03T19:30:43.635Z",
        "updatedAt": "2021-09-03T19:31:08.175Z",
        "__v": 0,
        "id": "613277e3fb9e183ee8b1a136"
    },
    "id": "613277fcfb9e183ee8b1a137"
}
```
{% endapi-method-response-example %}
{% endapi-method-response %}
{% endapi-method-spec %}
{% endapi-method %}

