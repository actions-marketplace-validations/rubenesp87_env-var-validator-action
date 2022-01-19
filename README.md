# env-var-validator-action

# Environment variable validator

Check that an environment variable file not contains empty values

## Inputs
### `filepath`

**Required** Path to a env var file.

## Example usage

```yaml
uses: rubenesp87/env-var-validator-action@latest
with:
  version: '.env'
```

```yaml
uses: rubenesp87/env-var-validator-action@latest
with:
  version: 'packages/.env.app'
```
