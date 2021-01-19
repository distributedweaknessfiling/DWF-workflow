# Workflow and tools

This repo is for defining workflow policy and storing the tooling to enforce
that policy.

For requesting CVE IDs, please see the project page here (add link when it
exists)

## Workflow

- User files issue
  - issue has information, urls, etc
  - issue is expected to be correct and reasonable
  - An automated system can check the URLs are valid and well formed
- Issue is turned into a CVE if user is approved and automated checks pass
- Issue is turned into a CAN if user is not on the approved list
  - Issues can be upgraded to CVE if proven to be correct and accurate
  - Some issues will be CAN IDs forever
  - DWF will not remove IDs that are invalid, but an appropriate comment will
    be added

## User approval

- Submit well formed CVE IDs on a consistent basis
- Assist with updating and vetting issues
- ???

## Process updates

The DWF is a community. Fundamentally if you want to see a proces or tool
improvement, submit an issue or a pull request. The people who do the work
decide the future of the community. The future is not decided by whoever is
able to "committee harder" during a meeting.
