# Idol Pride — EN Translation Data

Translation data consumed by the **Hoshimi Localify EN** module through the GitHub
`releases/latest` API.

- `version.txt` — the release version; also the release tag.
- `local-files/` — the translation payload the app extracts.

A push to `main` packages `version.txt` + `local-files/` into a single `.zip` release asset.
The latest release is the app's update feed.

Pushing an unchanged `version.txt` is a no-op: the workflow's tag guard detects the
existing release and skips creating a duplicate.

This repository is a sanitized mirror; the source of truth is a private repository.

