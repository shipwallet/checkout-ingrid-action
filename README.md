# Checkout Ingrid Actions

**This action is now deprecated. Please use [this one](https://github.com/shipwallet/setup-ingrid-context) instead.**

**This is a public repository**

This repo contains the GitHub Action used to download the latest version of our custom actions.

The repository where the actions are stored is a private repository within our Organization.

# Usage

This action uses an environment variable name `GH_TOKEN_SW_BOT` to authenticate and checkout the private repo.

<!-- start usage -->
```yaml
- uses: shipwallet/checkout-ingrid-actions@v1
  with:
    # Path where the code should be checked out
    # Default: ingrid-actions
    path: ''

    # The branch, tag or SHA to checkout. When checking out the repository that
    # triggered a workflow, this defaults to the reference or SHA for that event.
    # Otherwise, uses the default branch.
    ref: ''
```
<!-- end usage -->
