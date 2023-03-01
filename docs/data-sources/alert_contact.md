---
page_title: "uptimerobot_alert_contact Data Source - terraform-provider-uptimerobot"
subcategory: ""
description: |-
  Get information about your alert contact
---

# Data Source: uptimerobot_alert_contact

Use this data source to get information about the alert contacts.

## Example Usage

```hcl
data "uptimerobot_alert_contact" "main" {}
```

## Attributes Reference

* `friendly_name` - friendly name of the alert contact.
* `id` - the ID of the alert contact.
* `type` - the type of the alert contact notified
* `status` - the status of the alert contact.