# 🏠 saya6k Home Assistant add-on repository

[![License](https://img.shields.io/github/license/saya6k/hassio-addons.svg)](LICENSE)
[![GitHub issues](https://img.shields.io/github/issues/saya6k/hassio-addons)](https://github.com/saya6k/hassio-addons/issues)
[![Last Commit](https://img.shields.io/github/last-commit/saya6k/hassio-addons)](https://github.com/saya6k/hassio-addons/commits/main)
[![Stars](https://img.shields.io/github/stars/saya6k/hassio-addons)](https://github.com/saya6k/hassio-addons/stargazers)

> My Personal Home Assistant Add-on collection for extending functionality and automating daily tasks.

Add-on documentation: <https://developers.home-assistant.io/docs/add-ons>

## ⚡ Installation

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fsaya6k%2Fhassio-addons)

1. Navigate to the Home Assistant Supervisor panel
2. Click on "Add-on Store" in the menu
3. Click the 3-dots menu at the top right and select "Repositories"
4. Add the URL: `https://github.com/saya6k/hassio-addons`
5. The add-ons from this repository will now show under "Local Add-ons"

## 📦 Available Add-ons

This repository contains the following add-ons:

### [Brother-QL-Web](https://github.com/saya6k/hassio-addon-brother-ql-web)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
[![GitHub Release][brother-ql-web-release-shield]][brother-ql-web-release]
[![Submodule](https://img.shields.io/badge/submodule-brother-ql-web: unknown)](https://github.com/saya6k/hassio-addon-brother-ql-web)

_Brother-QL Web add-on to print labels on Brother Label Printers._

### [ytdlp2STRM](https://github.com/saya6k/hassio-addon-ytdlp2strm)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
[![GitHub Release][ytdlp2strm-release-shield]][ytdlp2strm-release]

_ytdlp2STRM add-on to convert Youtube & Twitch Live stream as strm files._

### [mcp-grocy-api](https://github.com/saya6k/mcp-grocy-api)

![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
[![GitHub Release][mcp-grocy-release-shield]][mcp-grocy-release]
![Submodule Status](https://byob.yarr.is/saya6k/hassio-addons/mcp-grocy-api: 43b6f86)](https://github.com/saya6k/mcp-grocy-api/tree/43b6f86)

_mcp-grocy-api add-on to support MCP(model context protocol) with Grocy._

## 📝 Contributing

Contributions to improve these add-ons are welcome! Please feel free to submit a PR or open an issue.

<!--

Notes to developers after forking or using the github template feature:
- While developing comment out the 'image' key from 'example/config.yaml' to make the supervisor build the addon
  - Remember to put this back when pushing up your changes.
- When you merge to the 'main' branch of your repository a new build will be triggered.
  - Make sure you adjust the 'version' key in 'example/config.yaml' when you do that.
  - Make sure you update 'example/CHANGELOG.md' when you do that.
  - The first time this runs you might need to adjust the image configuration on github container registry to make it public
  - You may also need to adjust the github Actions configuration (Settings > Actions > General > Workflow > Read & Write)
- Adjust the 'image' key in 'example/config.yaml' so it points to your username instead of 'home-assistant'.
  - This is where the build images will be published to.
- Rename the example directory.
  - The 'slug' key in 'example/config.yaml' should match the directory name.
- Adjust all keys/url's that points to 'home-assistant' to now point to your user/fork.
- Share your repository on the forums https://community.home-assistant.io/c/projects/9
- Do awesome stuff!
 -->

[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[brother-ql-web-release-shield]: https://img.shields.io/github/release/saya6k/hassio-addon-brother-ql-web.svg
[brother-ql-web-release]: https://github.com/saya6k/hassio-addon-brother-ql-web/releases
[ytdlp2strm-release-shield]: https://img.shields.io/github/release/saya6k/hassio-addon-ytdlp2strm.svg
[ytdlp2strm-release]: https://github.com/saya6k/hassio-addon-ytdlp2strm/releases
[mcp-grocy-release-shield]: https://img.shields.io/github/release/saya6k/mcp-grocy-api.svg
[mcp-grocy-release]: https://github.com/saya6k/mcp-grocy-api/releases
