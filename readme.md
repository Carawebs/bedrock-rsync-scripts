Rsync Utilities
===============
**In development, use with caution.**

Synchronise Bedrock `config` directory from local to staging or production.

## Usage Example: `sync-form-settings`
- Clone this repo
- `cd` into the repo
- Copy `/config/variables-staging-sample` to a suitable filename: `config/variables-staging` and amend variables as necessary
- Ensure that `sync-config` is executable
- Run `./sync-config staging` to sync configuration settings from the local to the staging remote environment

To set up a production environment, set up `private/common-variables-production`
 and `private/form-settings-variables-production`
