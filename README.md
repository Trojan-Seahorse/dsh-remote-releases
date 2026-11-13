# DSH Remote releases

Public release channel for **DSH Remote**, a lightweight Windows client for a
remote DSH host. The source repository is private; this repository only hosts
signed installers and the updater feed.

## Latest release

**0.1.5** — Windows x64 NSIS installer

- Installer SHA256: `1c136d0dbbb91698b02f4dce624519e8eda2f85df8f40bc0d992c541a0533696`
- Release page: https://github.com/Trojan-Seahorse/dsh-remote-releases/releases/latest

## Updater feed

`https://github.com/Trojan-Seahorse/dsh-remote-releases/releases/latest/download/latest.json`

## Verify

Each release includes:

- `DSH Remote_<version>_x64-setup.exe`
- `dsh-remote_<version>_x64-setup.exe` (updater asset)
- `.sig` updater signature
- `latest.json`
- `SHA256SUMS-<version>.txt`

Installer is signed by `Duke Ewell Laboratory`; verify with
`Get-AuthenticodeSignature` on Windows. Release assets are public; do not post
secrets or private host details here.
