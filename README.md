# .github

This repository contains organization-wide GitHub workflow templates and other configuration files for our organization.

## Workflow Templates

### auto-author-assign

Automatically assigns PR and issue authors as assignees

**Usage:**
To use this template in your repository, navigate to the "Actions" tab, click "New workflow," and select "Auto Author Assign Workflow" from the organization templates. No additional configuration is required for basic functionality, but you can customize the workflow by modifying trigger events or using a custom token by editing the `.github/workflows/auto-author-assign.yml` file after adding it to your repository.

### docapprover

Automatically approves doc PRs, and rejects those that have non-doc changes.

**Usage:**
To use this template in your repository, navigate to the "Actions" tab, click "New workflow," and select "Doc Approver Workflow" from the organization templates. No additional configuration is required for basic functionality, but you can customize the workflow by modifying trigger events or using a custom token by editing the `.github/workflows/doc-approval.yml` file after adding it to your repository.
