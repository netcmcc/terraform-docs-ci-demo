<!-- BEGIN_TF_DOCS -->
# Terraform Docs CI Example

Everything in this comment block will get extracted.

You can put simple text or complete Markdown content
here. Subsequently if you want to render AsciiDoc format
you can put AsciiDoc compatible content in this comment
block.

## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.1.2 |
| <a name="requirement_tencentcloud"></a> [tencentcloud](#requirement\_tencentcloud) | 1.77.3 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_tencentcloud"></a> [tencentcloud](#provider\_tencentcloud) | 1.77.3 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [tencentcloud_cos_bucket.tfstate](https://registry.terraform.io/providers/tencentcloudstack/tencentcloud/1.77.3/docs/resources/cos_bucket) | resource |
| [tencentcloud_user_info.current](https://registry.terraform.io/providers/tencentcloudstack/tencentcloud/1.77.3/docs/data-sources/user_info) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_bucket_prefix"></a> [bucket\_prefix](#input\_bucket\_prefix) | The Terraform state Bucket prefix (i.e.: `tfstate`) | `string` | n/a | yes |
| <a name="input_region"></a> [region](#input\_region) | The Tencent Cloud region (i.e.: `ap-guangzhou`) | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_bucket_name"></a> [bucket\_name](#output\_bucket\_name) | COS bucket name |
| <a name="output_cos_bucket_url"></a> [cos\_bucket\_url](#output\_cos\_bucket\_url) | COS bucket name |
<!-- END_TF_DOCS -->