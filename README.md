# Checkout Ingrid Actions

**This is a public repository**

This repo contains the GitHub Action used to download the latest version of our custom actions.

The repository where the actions are stored is a private repository within our Organization.

# Usage

This action requires a GitHub Token as part of the environment variables named as `GH_TOKEN`.

<!-- start usage -->
```yaml
- uses: shipwallet/checkout-ingrid-actions@master
  with:
    # Path where the code should be checked out
    # Default: ingrid-actions
    path: ''
```
<!-- end usage -->
