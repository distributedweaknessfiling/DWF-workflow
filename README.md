# About DWF

DWF is not approved of, by, or affiliated with MITRE. DWF is community project to assign security identifiers. We would love it if you joined us!

DWF IDs take the form of the string "DWF", a hyphen, a 4 digit year "YYYY," a hyphen, then an integer identifier XXXXXXX. The integers start at 1000000. Anything that starts with "CVE" is a CVE ID. Anything above one million and starts with "DWF" is a DWF ID. So for example DWF-2021-1000000.

# Workflow and tools

This repo is for defining workflow policy and storing the tooling to enforce
that policy.

For requesting DWF IDs, please see the project page at
https://iwantacve.org

The FAQ can be found here
https://github.com/distributedweaknessfiling/dwf-workflow/blob/main/FAQ.md

If you are looking for the actual IDs
https://github.com/distributedweaknessfiling/dwflist

If you want to see the tools that drive everything
https://github.com/distributedweaknessfiling/dwf-request

For all other requests, please file an issue in this repository.

## Expectations
The single most important expectation we have is to involve humans as little as possible. When requesting an ID, we don't want to be slow, and we don't want to rely on humans. At first there will be plenty of human involvement as we work out some of the details. Long term, no human should be involved. Humans are slow and make too many mistakes.

## Workflow
There are multiple workflows that take place.

1) User requests ID
    - issue has information, urls, etc
    - issue is expected to be correct and reasonable
    - ID is requested via web form
    - We do not have a good process for updating ID data today, we will need this
1) DWF bot looks for new issue
    - If requester is on the allow list, a DWF is assigned, the issue is closed
    - If requester is not on the allow list, a CAN is assigned, the issue remains open

1) A person on the allow list just has to add the "approved" flag
    - Adding a comment is not needed but encouraged
3) DWF bot looks for CAN IDs that have the approved flag
    - If approver is on the allow list, flip the CAN to DWF
    - If approver is not on the allow list, remove the approved label

## User approval

- Submit well formed DWF IDs on a consistent basis
- Assist with updating and vetting issues
- ???

## Process updates

The DWF is a community. Fundamentally if you want to see a proces or tool
improvement, submit an issue or a pull request. The people who do the work
decide the future of the community. The future is not decided by whoever is
able to "committee harder" during a meeting.

The tools that drive the reqeusts can be found [here](https://github.com/distributedweaknessfiling/dwf-request), patches are always welcome. If you have suggestions or questions, please file an issue.

# Where to file issues

## Tooling discussion
Please file issues about the tooling in the dwf-request repo: https://github.com/distributedweaknessfiling/dwf-request/issues

## Contesting/disputing a DWF ID

If you think a DWF ID contains an error or isn't valid please file an issue in the dwflist repo: https://github.com/distributedweaknessfiling/dwflist/issues

## General discussion of DWF IDs and the project

If you want to discuss workflow or the DWF ID project in general please use the dwf-workflow repo: https://github.com/distributedweaknessfiling/dwf-workflow/issues
