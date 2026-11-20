# Public distribution repository

- Keep proprietary Smart Control application sources in the separate private source repository.
- Publish exactly one full Windows installer per release: `Smart-Control-Setup.exe`.
- Publish the separate existing-installation update as `ClientUpdate.exe`.
- Never create full-installer duplicates or compatibility aliases such as `Setup.exe`.
- The main permanent link is `https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/Smart-Control-Setup.exe`.
- Keep `SHA256SUMS.txt` and `VALIDATION.json` consistent with the actual published asset names, sizes and SHA-256 values; preserve existing test scope/results.
- Before deleting a legacy download asset, check deployed website links. If an active website uses it, notify the owner before deletion.
