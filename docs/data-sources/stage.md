---
page_title: "authentik_stage Data Source - terraform-provider-authentik"
subcategory: "Flows & Stages"
description: |-
  Get stages by name
---

# authentik_stage (Data Source)

Get stages by name

## Example Usage

```terraform
# To get the ID of a stage by name

data "authentik_stage" "default-authentication-identification" {
  name = "default-authentication-identification"
}

# Then use `data.authentik_stage.default-authentication-identification.id`
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `name` (String)

### Read-Only

- `id` (String) The ID of this resource.