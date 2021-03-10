# DWF FAQ

# Why are you doing this?
We believe that the world needs good community driven secuirty identifiers. These do not currently exist. All current securiyt identifiers are tied to a company and do not represent the interest of the security community. A community can work very fast and do amazing work. Look at open source. DWF is open source.

# Why not work with MITRE?
We have tried in the past to work with MITRE to bring legacy CVE into the future. Having had no luck with this we have decided to bring back the DWF project. DWF is not CVE, it's just compatible with CVE.

# Are these real CVE IDs?
These are not CVE IDs, these are DWF IDs. They do however start with the 3 letters 'CVE'. DWF IDS will take the form of CVE-YYYY-XXXXXXX, the numerical part of the ID is always an integer greater than 1 million.

# Why use CVE in the identifier, why not use DWF?
CVE now means "vulnerability" in the same way a tissue is a kleenex.
If we create a "new" naming scheme we end up with [XKCD 927](https://xkcd.com/927/).
if we reuse an existing naming scheme, there isn't an increase in identifiers names.

We have staked out a claim well outside a range that could possible be a concern, that's why the 1 million. It's a huge number that probably won't have any collisions (possibly ever, but at least for decades).

# I don't have a github account
This is a dealbreaker if you want to submit IDs to the project. You can try to find a different project member to submit ID details on your behalf.

# Will DWF project track the mapping between DWFs and Mitre-CVEs?
## scenario: a DWF ID was issued to an issue, days/months later a CVE ID (Mitre-ecosystem CVE) was assigned to the same exact issue (enough details were available to accurately determine that both IDs are for the same issue).

At this time we expec to defer to MITRE's IDs. If there is a duplicate, the DWF ID wil be marked as such.

