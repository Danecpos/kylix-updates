# KYLIX Studio – updates

Update server for **KYLIX Studio** (tools for DaVinci Resolve by KYLIX).

KYLIX Studio checks `manifest.json` here and downloads only the tools that changed.

- `manifest.json` is signed (Ed25519) – the tools refuse any manifest that is not signed by KYLIX.
- `pkgs/*.kpk` are encrypted packages – they open only with a valid KYLIX licence.

Nothing here needs to be downloaded by hand. Buy KYLIX Studio at Motionframe Assets.
