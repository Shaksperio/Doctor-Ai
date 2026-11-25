# NOTICE

Doctor Ai is a derivative work of **Doctor Dok**.

## Original work

- Project: Doctor Dok
- Authors / copyright holder: **Catch The Tornado** (Copyright (c) 2024 Catch The Tornado)
- Upstream repository: https://github.com/Doctor-One/doctor-dok (formerly https://github.com/CatchTheTornado/doctor-dok)
- Base commit: `727ca70` (28 June 2025, "Merge pull request #271 from Doctor-One/feat_partial_loads")
- License: MIT. The full license text and the original copyright notice are kept unchanged in [LICENSE](LICENSE), as the license requires for copies and substantial portions of the software.

The architecture and most of the code in this repository originate from the upstream authors, including the client-side encryption flow, the folder/record/attachment data model, the AI parsing and chat pipeline, the OCR integration and the REST API.

## Changes made in this repository

- Renamed the project to Doctor Ai (package name, UI texts, manifest, export file names, JWT issuer/audience).
- Replaced logos, icons and favicon with new placeholder artwork; removed upstream brand images and screenshots.
- Removed upstream contact details; the contact address is now read from `NEXT_PUBLIC_CONTACT_EMAIL`.
- Replaced the upstream Terms of Service and Privacy Policy (which describe a different legal entity) with drafts that must be reviewed before production use.
- Rewrote README and SECURITY policy; source-code links in `docs/api` now point to this repository.

References to upstream design documents (for example issue #65 on the architecture) are intentionally kept as credits.

## Trademarks

"Doctor Dok", "Doctor-One" and "Catch The Tornado" and their logos belong to their respective owners. The MIT license does not grant rights to use them, and they are not used here to suggest endorsement.

## Third-party software

Dependencies listed in `package.json` are distributed under their own licenses.
