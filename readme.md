Rsync Utilities
===============
**In development, use with caution.**
These utilities are designed to facilitate syncronising local file-based configuration with a remote server.

Scripts accept an environment variable: 'staging' or 'production'.

## Usage Example: `sync-form-settings`
- Clone this repo
- `cd` into the repo
- Copy `/private/common-variables-staging-sample` to a suitable filename: `private/common-variables-staging` and amend variables
- Copy `private/form-settings-variables-staging-sample` to a suitable filename: `private/form-settings-variables-staging` and amend variables for the form-settings paths (locally and on the server)
- Ensure that `sync-form-settings` is executable
- Run `./sync-form-settings staging` to sync form settings from the local to the staging remote environment

To set up a production environment, set up `private/common-variables-production`
 and `private/form-settings-variables-production`
