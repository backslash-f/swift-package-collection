[![swift-package-manager](https://img.shields.io/badge/package%20manager-compatible-d5b561.svg?logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4KPHN2ZyB3aWR0aD0iNjJweCIgaGVpZ2h0PSI0OXB4IiB2aWV3Qm94PSIwIDAgNjIgNDkiIHZlcnNpb249IjEuMSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayI+CiAgICA8IS0tIEdlbmVyYXRvcjogU2tldGNoIDYzLjEgKDkyNDUyKSAtIGh0dHBzOi8vc2tldGNoLmNvbSAtLT4KICAgIDx0aXRsZT5Hcm91cDwvdGl0bGU+CiAgICA8ZGVzYz5DcmVhdGVkIHdpdGggU2tldGNoLjwvZGVzYz4KICAgIDxnIGlkPSJQYWdlLTEiIHN0cm9rZT0ibm9uZSIgc3Ryb2tlLXdpZHRoPSIxIiBmaWxsPSJub25lIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiPgogICAgICAgIDxnIGlkPSJHcm91cCIgZmlsbC1ydWxlPSJub256ZXJvIj4KICAgICAgICAgICAgPHBvbHlnb24gaWQ9IlBhdGgiIGZpbGw9IiNEQkI1NTEiIHBvaW50cz0iNTEuMzEwMzQ0OCAwIDEwLjY4OTY1NTIgMCAwIDEzLjUxNzI0MTQgMCA0OSA2MiA0OSA2MiAxMy41MTcyNDE0Ij48L3BvbHlnb24+CiAgICAgICAgICAgIDxwb2x5Z29uIGlkPSJQYXRoIiBmaWxsPSIjRjdFM0FGIiBwb2ludHM9IjI3IDI1IDMxIDI1IDM1IDI1IDM3IDI1IDM3IDE0IDI1IDE0IDI1IDI1Ij48L3BvbHlnb24+CiAgICAgICAgICAgIDxwb2x5Z29uIGlkPSJQYXRoIiBmaWxsPSIjRUZDNzVFIiBwb2ludHM9IjEwLjY4OTY1NTIgMCAwIDE0IDYyIDE0IDUxLjMxMDM0NDggMCI+PC9wb2x5Z29uPgogICAgICAgICAgICA8cG9seWdvbiBpZD0iUmVjdGFuZ2xlIiBmaWxsPSIjRjdFM0FGIiBwb2ludHM9IjI3IDAgMzUgMCAzNyAxNCAyNSAxNCI+PC9wb2x5Z29uPgogICAgICAgIDwvZz4KICAgIDwvZz4KPC9zdmc+)](https://github.com/apple/swift-package-manager)

# Swift Package Collection 📦
A collection of my Swift Packages, based on the WWDC21 session [Discover and curate Swift Packages using Collections](https://developer.apple.com/videos/play/wwdc2021/10197/).

>Whether you're curating packages for your team, for education purposes, or to share with other developers, Swift Package Collections can help you discover, explore, and import new packages into your project.
>
>Discover improvements in the Swift Package workflow using Collections, and learn how you can curate, create, sign, and share your own Swift Package Collections.

# Packages
- 🔒 [AESCryptable](https://github.com/backslash-f/aescryptable): AES encryption/decryption with random iv
- 👾 [ALMA](https://github.com/backslash-f/alma): Game Engine for the Apple ecosystem
- 📒 [AppLogger](https://github.com/backslash-f/applogger): Wrapper around Apple's Swift logging APIs
- 🔀 [CGKStateMachine](https://github.com/backslash-f/cgkstatemachine): Allows GKState changes to be observed via Combine
- 🌃 [CSKScene](https://github.com/backslash-f/cskscene): Custom SKScene with debugging features and game controller observing capabilities
- 📱 [Device](https://github.com/backslash-f/device): Retrieves information about the host device
- ⚙️ [Extensions](https://github.com/backslash-f/extensions): A collection of useful Swift/SwiftUI extensions
- 🎮 [GCOverseer](https://github.com/backslash-f/gcoverseer): Observe and manage game controllers using Combine
- 🖼 [SImage](https://github.com/backslash-f/simage): Multiplatform Core Graphics wrapper
- 🧰 [Toolbox](https://github.com/backslash-f/toolbox): A collection of useful Swift tools
- 🤑 [SwiftTrader](https://github.com/backslash-f/swift-trader): A package for connecting and trading on crypto exchanges via REST

# Integration

## Terminal

`swift package-collection add https://raw.githubusercontent.com/backslash-f/swift-package-collection/main/collection.json --skip-signature-check --trust-unsigned`

##### `--skip-signature-check`/`--trust-unsigned`?
Signing is currently broken for me. :-(

## Xcode

- File / Add Package Dependencies...
- Click on the `+` button at the bottom-left / Add Package Collection
- URL: `https://raw.githubusercontent.com/backslash-f/swift-package-collection/main/collection.json`

- Tap on Load / Add Collection

The collection should show up:

![swift package collection](https://raw.githubusercontent.com/backslash-f/swift-package-collection/main/packages.png)
