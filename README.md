# Fresh USA Smart Control — Windows Downloads

Official installer downloads for **Fresh USA Smart Control 2.1.0.5**: RFID inventory, Smart Storage, asset movements, touch-friendly checkout, anti-theft monitoring, optional product photos and Business Insights & Analytics.

## Download

- **[Full offline installer — Smart-Control-Setup.exe](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/Smart-Control-Setup.exe)** — for a new Windows x64 computer. Includes dedicated SQL Server 2022 Express and required components. Approximately 1.41 GB.
- **[Client update — ClientUpdate.exe](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/ClientUpdate.exe)** — for an existing Smart Control installation. Keeps its database, settings and license. Approximately 147 MB. Close Smart Control before updating.
- **[SHA-256 checksums](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/SHA256SUMS.txt)** and **[validation report](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/VALIDATION.json)**.

Downloads are public and do not require a GitHub account. These `latest/download` addresses remain the same for future stable releases when the same asset names are retained. Each release contains exactly one full installer, named `Smart-Control-Setup.exe`, and the separate `ClientUpdate.exe` update package. No duplicate full-installer aliases are published. For a specific version, use [Releases](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases).

## Installation and activation

Run the installer, read and accept the license agreement, and choose a standalone database, shared host or client workstation. Installation starts in English and provides desktop and Start-menu shortcuts. Keep existing settings when updating. A separate valid Smart Control license is required; downloading the installer does not grant activation or a license.

The English (US) User Guide and Quick Start are included and open offline from **Settings → Help & Support**. The interface supports English (US), Spanish, French, Portuguese, Russian and Arabic.

Square account authorization, terminal pairing and register assignment are integrated into Smart Control. No separate Square setup application is required. Other payment-terminal integrations are available by arrangement with Fresh USA.

## Verification

The exact 2.1.0.5 installers passed clean Windows/SQL installation, an actual update from 2.0.16, standard Windows user SQL permissions, desktop/Start shortcuts, application launch and close, repair, cached recovery and data preservation during uninstall. Software and native WPF regression suites passed. Shelf quantities use confirmed presence during brief RF read gaps while retaining the existing removal countdown and reader settings.

The owner previously confirmed physical F-02, F-920, F-950 and Square Terminal S149 scenarios on 2.0.16. This is baseline evidence; new-build physical RFID scenarios, physical multi-PC LAN and new live Square payments/refunds are **NOT_RUN** for 2.1.0.5. See the validation report for the exact scope.

The installer is currently **not Authenticode-signed**. Verify its SHA-256 against the published checksum file.

Product source code is maintained separately. This public repository contains distribution information and release automation, not proprietary application sources. Older published releases remain available.

Software is provided as is under the included Fresh USA EULA. For licensing, setup, support, customization and other POS integrations, contact **Fresh USA, Inc.**: [fresh222.com](https://fresh222.com) · fresh@fresh222.com.
