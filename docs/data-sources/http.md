---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "http Data Source - terraform-provider-http-full"
subcategory: ""
description: |-
  
---

# http (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `url` (String)

### Optional

- `ca` (String)
- `client_crt` (String)
- `client_key` (String, Sensitive)
- `method` (String)
- `request_body` (String)
- `request_headers` (Map of String)

### Read-Only

- `body` (String)
- `id` (String) The ID of this resource.
- `response_headers` (Map of String)
- `status_code` (Number)


