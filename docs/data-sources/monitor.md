---
page_title: "uptimerobot_monitor Data Source - terraform-provider-uptimerobot"
subcategory: ""
description: |-
  Get information about monitors
---

# Data Source: uptimerobot_monitor

Use this data source to get information about the monitors.

## Example Usage

```hcl
data "uptimerobot_monitor" "main" {}
```

## Attributes Reference

* `id` - the ID of the monitor (can be used for monitor-specific requests)
* `friendly_name` - friendly name of the monitor (for making it easier to distinguish from others).
* `url` - the URL/IP of the monitor.
* `type` - the type of the monitor. Can be one of the following:
* `status` - the status of the monitor.
* `interval` - the interval for the monitoring check.
* `sub_type` - which service is monitored.
* `port` - which port is monitored or if a custom port is monitored.
* `keyword_type` - if the monitor will be flagged as down when the keyword exists or not exists.
* `keyword_value` - the value of the keyword.
