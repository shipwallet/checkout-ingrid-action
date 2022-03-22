# Checkout Ingrid Actions

**This is a public repository**

This repo contains the GitHub Action used to download the latest version of our custom actions.

The repository where the actions are stored is a private repository within our Organization.

# Usage



<!-- start usage -->
```yaml
- uses: shipwallet/checkout-ingrid-actions@v1
  with:
    # GitHub token which has access to clone the private repo in the Organization
    # Default: This takes by default the value of the environment variables named as `GH_TOKEN`.
    github-token: ''
    
    # Path where the code should be checked out
    # Default: ingrid-actions
    path: ''

    # The branch, tag or SHA to checkout. When checking out the repository that
    # triggered a workflow, this defaults to the reference or SHA for that event.
    # Otherwise, uses the default branch.
    ref: ''
```
<!-- end usage -->
