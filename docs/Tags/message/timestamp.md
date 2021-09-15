---
description: Returns the time the message was sent. "exact" is a boolean indicating whether to include hours/minutes.
---
# {message.timestamp;[exact];[message id];[message channel]}
## Examples
{% tabs %}
{% tab title="Input" %}
```text
{message.timestamp}
```
{% endtab %}
{% tab title="Output" %}
```text
Nov 4, 2015
```
{% endtab %}
{% endtabs %}
{% tabs %}
{% tab title="Input" %}
```text
{message.timestamp;true}
```
{% endtab %}
{% tab title="Output" %}
```text
Nov 4, 2015, 7:53 AM
```
{% endtab %}
{% endtabs %}