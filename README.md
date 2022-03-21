# Checkout Ingrid Actions

This repo contains the GitHub Action used to download the latest version of our custom actions.

The repository where the actions are stored is a private repository within our Organization.

# Usage

<!-- start usage -->
```yaml
- uses: shipwallet/checkout-ingrid-actions@master
  with:
    # GitHub token which has access to clone the private repo in the Organization
    github-token: ''

    # Path where the code should be checked out
    # Default: ingrid-actions
    path: ''
```
<!-- end usage -->
