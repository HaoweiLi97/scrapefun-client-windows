# ScrapeFun Client for Windows

[简体中文](./README.md) · **English**

[Product overview](https://github.com/HaoweiLi97/ScrapeFun/blob/main/README.en.md) · [Stable downloads](https://github.com/HaoweiLi97/scrapefun-client-windows/releases/latest) · [All releases](https://github.com/HaoweiLi97/scrapefun-client-windows/releases) · [Online documentation](https://scrapefun.com/?lang=en#/docs)

> Updated: 2026-09-28. Versions and assets below are the stable releases checked on this date. Follow the corresponding Release for later changes.

Windows desktop client for connecting to an existing ScrapeFun Server, browsing movie and TV resources, using the native player, and reading comics. Client and Server are installed and updated separately.

## Downloads and environment

| Item | Current stable release |
| --- | --- |
| Version | [0.0.5](https://github.com/HaoweiLi97/scrapefun-client-windows/releases/tag/v0.0.5) |
| Architecture | This installer supports both x64 / ARM64 |
| Manual installation | `scrapefun-client-electron-windows-0.0.5-stable-x64-setup.exe` |
| Update assets | `latest.yml`, installer `.blockmap` |

Download setup from the [stable download page](https://github.com/HaoweiLi97/scrapefun-client-windows/releases/latest). Although the 0.0.5 filename includes `x64`, its release notes explicitly state x64 and ARM64 support. Recheck other versions rather than assuming the same support.

Version 0.0.5 is not Windows code signed and may show an unknown-publisher message on first installation. Verify the official source and release after downloading. That message does not mean the package has a publisher signature.

## Installation and connection

1. Run setup, follow the installation wizard, and launch ScrapeFun Client.
2. Enter the Server address, such as `http://192.168.1.10:8096`.
3. Sign in with your Server account.

Version 0.0.5 can discover servers from the connection page. Discovery requires a Server on the LAN that supports it. If no result appears, enter the address manually. Discovery does not replace connection checks or login.

## Updates and configuration

Use the client's update mechanism or run newer setup over the existing installation. The same user's server connection settings are normally retained. Do not delete the client's user configuration directory. Stop playback during the update and reconnect to Server afterward.

## Troubleshooting

For connection problems, first check Server status, address, port, and firewall. For playback issues, include Windows version, CPU architecture, Server and Client versions, media codecs, and logs with sensitive details removed.

## Support and licensing

This repository provides platform installation instructions and official release assets. Submit usage questions and feature requests to the [main repository Issues](https://github.com/HaoweiLi97/ScrapeFun/issues). For accounts, activation, or private logs, contact `scrapefun@outlook.com`. Report security issues privately according to the [security instructions](./SECURITY.en.md).

See the new [commercial license statement](./LICENSE.en.txt) and full [software license agreement](./EULA.en.md). Ordinary personal, household, and internal organizational use is allowed. Pro requires a valid entitlement. Software redistribution, resale, customer delivery, and paid hosting require separate written authorization. The statement does not retroactively change existing licenses; existing assets follow their supplied licenses, and third-party components retain their own licenses.

[Releases and compatibility](https://github.com/HaoweiLi97/ScrapeFun/blob/main/RELEASE_POLICY.en.md) · [Third-party components](https://github.com/HaoweiLi97/ScrapeFun/blob/main/THIRD_PARTY_NOTICES.en.md) · [Support](./SUPPORT.en.md)
