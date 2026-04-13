# ci-runner

Public repo for running GitHub Actions workflows with free unlimited minutes.

Workflows here check out private repos and run CI/CD tasks — deployments, infrastructure provisioning, etc.

## Secrets needed

All secrets/variables from your private repos must be duplicated here.

## Current workflows

- **OCI ARM Capacity Watch** — tries to create ARM instances every 5 min across all Ashburn ADs
