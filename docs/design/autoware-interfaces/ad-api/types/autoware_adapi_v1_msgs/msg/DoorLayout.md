---
# This file is generated by tools/autoware-interfaces/generate.py
title: autoware_adapi_v1_msgs/msg/DoorLayout
used:
  - autoware_adapi_v1_msgs/srv/GetDoorLayout
---

{% extends 'design/autoware-interfaces/templates/autoware-data-type.jinja2' %}
{% block definition %}

```txt
uint8 GET_ON = 1
uint8 GET_OFF = 2

uint8[] roles
string description
```

{% endblock %}