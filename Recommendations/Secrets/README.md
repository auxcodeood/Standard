# Secrets

This Recommendation deals w/ the question where to store Secrets such as passwords, API keys, environment variables, etc.

## Key Vault

...

## Code Repository

Code Repositories are per se secure.

The insecurity of repositories in relation to secrets come from the following facts:

* When stored in the code repository, more people might have access to a code repository, than those who have to have access to the Secrets.

* When stored in a specialised repository, repository is versioned, so deleting a Secret, does not remove it from the previous commits.
