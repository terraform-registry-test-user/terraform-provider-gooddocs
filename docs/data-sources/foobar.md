# gooddocs_foobar

This is to test same name between data-source and resource causes no conflict.

## Example Usage

```hcl
data "gooddocs_foobar" "example" {
	name = "the-foo-bar-experience"
}
```

## Argument Reference
The following arguments are supported:

* `name` - (Optional) The name of the source.

## Attributes Reference
The following attributes are exported:

* `id` - The ID of the service.
