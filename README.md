# glueops-backup-hashicorp-vault

![Version: 0.1.2](https://img.shields.io/badge/Version-0.1.2-informational?style=flat-square) ![AppVersion: v0.1.0](https://img.shields.io/badge/AppVersion-v0.1.0-informational?style=flat-square)

GlueOps Helm Chart for backing up Hashicorp Vault

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| aws_accessKey | string | `"nil"` |  |
| aws_region | string | `"nil"` |  |
| aws_secretKey | string | `"nil"` |  |
| captain_domain | string | `"nil"` |  |
| company_key | string | `"nil"` |  |
| cron_expression | string | `"0 */6 * * *"` |  |
