# Fresh USA Smart Control - Windows Downloads

Official installer downloads for **Fresh USA Smart Control 2.0.16**: RFID registration, Smart Storage, asset movements, checkout and anti-theft monitoring.

## Download

* **[Full offline installer - Setup.exe](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/Setup.exe)** - use for a new Windows x64 computer. Includes the dedicated SQL Server 2022 Express components and the mapped USB driver.
* **[Client update - ClientUpdate.exe](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/ClientUpdate.exe)** - use only when Smart Control is already installed. Keeps the existing database, settings and license.
* **[SHA-256 checksums](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/SHA256SUMS.txt)** and **[validation report](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases/latest/download/VALIDATION.json)**.

These addresses stay the same for future stable versions. For a specific immutable version, use [Releases](https://github.com/lerifresh-tech/Fresh-USA-Smart-Control-Download/releases).

## Installation and activation

Run the installer, read and accept the license agreement, and choose a standalone database, shared host or client workstation. Installation starts in English and provides desktop and Start-menu shortcuts. Keep existing settings when updating. A separate valid Smart Control license is required; downloading an installer does not grant activation or a license.

Square account authorization, terminal pairing and register assignment are integrated into Smart Control. No separate Square setup application is required. Contact Fresh USA about other payment-terminal integrations.

## Verified release

Application files were tested with real F-02, F-920 and F-950 RFID readers and Square Terminal S149. Release checks cover clean Windows installation with SQL, EULA consent, shortcuts, launch, repair and data preservation during uninstall. See the validation report for the exact build and checks.

The installer is currently **not Authenticode-signed**. Verify its SHA-256 against the published checksum file.

Product source code is maintained separately. This public repository contains distribution information and release automation, not the proprietary application sources. Published version assets are not overwritten.

Copyright Fresh USA, Inc. Contact: [fresh222.com](https://fresh222.com).
