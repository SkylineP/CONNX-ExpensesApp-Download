# Public download repository instructions

This repository contains approved Android installers and public installation documentation only.

- Build, sign and verify in the separate private development project. Obtain the repository owner's explicit approval for each specific artifact before publishing it here. Do not automatically mirror builds.
- Copy the exact approved APK without rebuilding or re-signing. Keep installers in versioned GitHub Release assets, outside Git source history.
- Before upload, review the APK's packaged contents and the complete upload staging folder for credentials, private keys, environment files, local databases, real receipts, reports, employee data, private paths, logs, source maps and other unintended internal files. Stop publication if anything unexpected is found.
- Publish only the approved APK, its SHA-256 checksum and minimal public build metadata. Allowed metadata includes app name, version, version code, architecture, byte size, checksum and signing-certificate fingerprint. A certificate fingerprint is public identification, never the private signing key.
- Keep internal repository names/URLs, private source revision identifiers, approval conversations, operator names and private build/evidence links out of public metadata, release notes and documentation.
- An approved APK download URL is intentionally public. Never place an API token, personal access token, credential-bearing URL or signing credential in a download link.
- Verify uploaded bytes and an anonymous download against the privately verified artifact before advertising the GitHub download as available.
- Keep English/French installation guidance, TEST status and acceptance limits accurate. Never advise uninstalling or clearing app data to update.
- Do not send employee notifications without authorization. Do not publish real receipts, expense reports or personal details in public issues.
- APK publication is pending. The README currently links to the approved temporary APK download; do not claim a GitHub release asset exists before upload and verification.
