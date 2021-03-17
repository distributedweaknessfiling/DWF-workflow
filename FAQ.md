# DWF FAQ

# Why are you doing this?
We believe that the world needs good community driven secuirty identifiers. These do not currently exist. All current securiyt identifiers are tied to a company and do not represent the interest of the security community. A community can work very fast and do amazing work. Look at open source. DWF is open source.

# Why not work with MITRE?
We have tried in the past to work with MITRE to bring legacy CVE into the future. Having had no luck with this we have decided to bring back the DWF project. DWF is not CVE, it's just compatible with CVE.

# Are these real CVE IDs?
These are not CVE IDs, these are DWF IDs. They start with the 3 letters, 'DWF.' DWF IDs will take the form of DWF-YYYY-XXXXXXX, the numerical part of the ID is always an integer greater than 1 million.

# I don't have a github account
This is a dealbreaker if you want to submit IDs to the project. You can try to find a different project member to submit ID details on your behalf.

# Will DWF project track the mapping between DWFs and CVEs?
## scenario: a DWF ID was issued to an issue, days/months later a CVE ID was assigned to the same exact issue (enough details were available to accurately determine that both IDs are for the same issue).

At this time we expec to defer to the CVE Project's IDs. If there is a duplicate, the DWF ID wil be marked as such.

# What is the "allow list"?

A list of people allowed to request DWF IDs without review e.g. trusted contributors. The list can be found [here](https://github.com/distributedweaknessfiling/dwflist/blob/main/allowlist.json)

# How do I get on the allow list?

You do some work. Submit IDs, review IDs, contribute PRs. The bar is pretty low, it's meant to keep out the riff raff.

# What if github goes away (or becomes restricted in its use in some way)?

GitHub is now critical open source infrastructure. If this does ever happen, we will deal with it as needed. We'll probably be OK for a while.

# What if github is blocked in a country/region/IP-space from which a user wants to submit?

We don't have a good answer for this today. Without GitHub we cannot run this project. Someday in the future we can revisit this.

# How do we stop potential scammers from just creating a host of false issues (perhaps via multiple throwaway github accounts)?

It's hard to create a lot of throwaway github accounts. We don't have a denylist yet, but will create one if needed. We also assign a CAN ID for unknown reporters. An untrusted user cannot get a DWF ID without someone trusted approving their request.
