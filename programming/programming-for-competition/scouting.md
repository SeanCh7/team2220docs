# Scouting

The most prominent source of data used in scouting is The Blue Alliance. View the example API method below.

{% swagger method="get" path="/status" baseUrl="https://www.thebluealliance.com/api/v3" summary="" %}
{% swagger-description %}

{% endswagger-description %}

{% swagger-parameter in="query" required="true" name="X-TBA-Auth-Key" type="String" %}
Get a key from your 

[Blue Alliance Dashboard](https://www.thebluealliance.com/account)

.
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="Successful Response" %}
```javascript
{
  "current_season": 0,
  "max_season": 0,
  "is_datafeed_down": true,
  "down_events": [
    "string"
  ],
  "ios": {
    "min_app_version": 0,
    "latest_app_version": 0
  },
  "android": {
    "min_app_version": 0,
    "latest_app_version": 0
  }
}
```
{% endswagger-response %}

{% swagger-response status="304: Not Modified" description="Not Modified: Use cached value" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}

{% swagger-response status="401: Unauthorized" description="" %}
```javascript
{
    // Response
}
```
{% endswagger-response %}
{% endswagger %}
