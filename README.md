# RacePoint-Live-Releases

Official Windows x64 application releases and automatic updates for RacePoint Live.

**[Download the Latest release](https://github.com/SteveMcGitub/RacePoint-Live-Releases/releases/latest).** Current stable release: [RacePoint Live v0.1.4](https://github.com/SteveMcGitub/RacePoint-Live-Releases/releases/tag/v0.1.4). Choose the RacePoint Live application ZIP, not GitHub's source-code archives.

For a new portable installation, download and extract the complete ZIP, then run the main **RacePoint Live.exe** inside the **RacePoint Live** folder. Keep **Updater**, **StarterContent**, **OfficialPresets**, and the other included files together. The .NET runtime is included; Visual Studio is not required. **Do not manually launch the helper inside the Updater folder**; start updates from the main application.

Existing users should select **Help / Check for Updates** and choose when to install a verified newer release. Close broadcast graphics, disconnect iRacing/replays and complete pending scoring before updating. Existing championships, profiles, selections and settings are preserved. v0.1.4 copies and verifies legacy `%LOCALAPPDATA%\TBPLivePoints` data before activating `%LOCALAPPDATA%\RacePointLive`; the legacy originals remain intact. Conflicts or failed verification stop startup with a warning rather than overwrite data. Do not delete or reset either data directory to upgrade. Follow **README-FIRST.txt** in the ZIP for the stable managed launcher used after the first portable update.

Windows SmartScreen may show a reputation warning because the executables are **not Authenticode-signed**. Automatic updates verify the separate production release-manifest signature and package checksums.
