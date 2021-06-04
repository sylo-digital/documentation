---
description: Returns the date the user joined the server at. "exact" is a true/false value on whether to include hours/minutes.
---

# user.joinedAt <exact> <user>

### Examples

{% tabs %}
{% tab title="Input" %}
```text
{user.joinedAt}
```
{% endtab %}

{% tab title="Output" %}
```text
Jul 28, 2017
```{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="Input" %}
```text
{user.joinedAt;true}
```
{% endtab %}

{% tab title="Output" %}
```text
Jul 28, 2017, 7:56 PM
```{% endtab %}
{% endtabs %}