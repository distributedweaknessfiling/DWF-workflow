# Workflow and tools

This repo is for defining workflow policy and storing the tooling to enforce that policy.

For requesting CVE IDs, please see the project page here (add link when it exists)

## Workflow

- User files issue
  - issue has information, urls, etc
  - issue is expected to be correct and reasonable
  - An automated system can check the URLs are valid and well formed
- Issue is turned into a CVE if user is approved and automated checks pass
- Issue is turned into a CAN if user is not on the approved list
  - Issues can be upgraded to CVE if proven to be correct and accurate
  - Some issues will be CAN IDs forever
  - DWF will not remove IDs that are invalid, but an appropriate comment will be added
