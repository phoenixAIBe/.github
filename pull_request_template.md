# Pull Request To Develop

## What

## Why

## Specification - Worksheet
*Add Link*

## Validation Checklist
- [ ] **Doc**: Documentation/Swagger have been written and validated.
- [ ] **Tests**: New or modified features have been tested.
- [ ] **Labels**: At least one label has been added (`feature`, `fix`, `chore`, etc.).
- [ ] **Description**: The **What** and **Why** sections are properly filled.
- [ ] **Linked ticket**: This PR is linked to the corresponding docs.
- [ ] **Issue**: Related issues are linked.
- [ ] **Change log**: The change log has been updated.
- [ ] **.env**: The version of the service has been updated in the **.env** file.
- [ ] **Secrets**: Github environment variables are configured with the **correct dev versions**.
- [ ] **Sonar**: SonarQube analysis passed successfully.
- [ ] **PR content**: The PR does contain only changes about one feature.
- [ ] **PR title**: The PR title follows the convention: `[FEATURE|FIX|...] Short description`.
- [ ] **README**: The README file has been updated.
- [ ] **Target branch**: The PR targets the develop branch.


# Merge Develop To Staging

- [ ] **Secrets**: Github environment variables are configured with the **correct staging versions**.
- [ ] **Change log**: The change log is complete and finalized for this release.
- [ ] **Release notes**: The release notes are completed and updated to reflect this release.
- [ ] **Service version**: The new version of the service has been validated according to the new features and fixes included.
- [ ] **Target branch**: The PR targets the staging branch.



# Merge Staging To Main

- [ ] **Secrets**: Github environment variables are configured with the **correct production versions**.
- [ ] **Change log**: The change log is complete and finalized for this release.
- [ ] **Spec**: A finalized version of the specification has been generated in **PDF** format.
- [ ] **Target branch**: The PR targets the main branch.
