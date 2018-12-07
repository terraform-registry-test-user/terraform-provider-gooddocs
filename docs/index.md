# GoodDocs Provider

Description paragraph for provider GoodDocs

## Example Usage

```hcl
# Configure the GoodDocs Provider
provider "gooddocs" {
	user_name = "admin"
	password = "admin"
}

resource "foobar" "example" {
	name = "the-foo-bar-experience"
}
```

## Argument Reference
The following arguments are supported:

* `user_name` - (Required) The username for HTTP basic authentication.
* `password` - (Required) The password to use for HTTP authentication.
* `arg1` - (Optional) arg1 description
* `arg2` - (Optional) arg2 description
