# Workflow and tools

This repo is for defining workflow policy and storing the tooling to enforce
that policy.

For requesting CVE IDs, please see the project page at https://iwantacve.org

## Workflow
There are multiple workflows that take place.

1) User requests ID
    - issue has information, urls, etc
    - issue is expected to be correct and reasonable
    - ID is requested via web form
1) DWF bot looks for new issue
    - If requester is on the allow list, a CVE is assigned, the issue is closed
    - If requester is not on the allow list, a CAN is assigned, the issue remains open
1) DWF bot looks for CAN IDs that have the approved flag
    - If approver is on the allow list, flip the CAN to CVE
    - If approver is not on the allow list, remove the approved label

## User approval

- Submit well formed CVE IDs on a consistent basis
- Assist with updating and vetting issues
- ???

## Process updates

The DWF is a community. Fundamentally if you want to see a proces or tool
improvement, submit an issue or a pull request. The people who do the work
decide the future of the community. The future is not decided by whoever is
able to "committee harder" during a meeting.
