---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "ametnes_kinds Data Source - terraform-provider-ametnes"
subcategory: ""
description: |-
  
---

# ametnes_kinds (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Read-Only

- `id` (String) The ID of this resource.
- `kinds` (List of Object) (see [below for nested schema](#nestedatt--kinds))

<a id="nestedatt--kinds"></a>
### Nested Schema for `kinds`

Read-Only:

- `backups` (List of Object) (see [below for nested schema](#nestedobjatt--kinds--backups))
- `enabled` (Boolean)
- `id` (String)
- `kind` (String)
- `limits` (List of Object) (see [below for nested schema](#nestedobjatt--kinds--limits))
- `locations` (List of String)
- `name` (String)
- `release` (String)
- `tools` (List of Object) (see [below for nested schema](#nestedobjatt--kinds--tools))
- `type` (String)

<a id="nestedobjatt--kinds--backups"></a>
### Nested Schema for `kinds.backups`

Read-Only:

- `enabled` (Boolean)


<a id="nestedobjatt--kinds--limits"></a>
### Nested Schema for `kinds.limits`

Read-Only:

- `nodes` (List of Number)


<a id="nestedobjatt--kinds--tools"></a>
### Nested Schema for `kinds.tools`

Read-Only:

- `enabled` (Boolean)


