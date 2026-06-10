# Status Badge Test

Scratch page for validating live Statuspage badges. **Not shown on the public org profile.**

## Internal Ops (test target)

[![Internal Ops Status](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Finternalopspage.statuspage.io%2Fapi%2Fv2%2Fstatus.json&query=%24.status.description&label=Internal%20Ops&color=b93be4&logo=statuspage&logoColor=white&cacheSeconds=60)](https://internalopspage.statuspage.io)

Notes:
- The badge text reflects `status.description` from the Statuspage API; color is fixed (Stax purple).
- The page must be **Active/published and public** for the badge to read it (otherwise the API returns 401).
- shields.io (~300s) and GitHub's camo image proxy cache the image — allow a few minutes after triggering an incident.
