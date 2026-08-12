# inneragents-bridge — releases

This repo hosts only the **distribution binaries** for `inneragents-bridge` — a native messaging host (Go) for the InnerAgents Chrome extension, giving it filesystem and shell access.

**No source code here.** Development happens in a private repo; this repo exists solely because GitHub doesn't allow public releases on a private repo — this is the only way to offer a download link that works without a GitHub account.

## Installation

Download the installer for your platform from the [latest release](../../releases/latest):

| OS | File |
|---|---|
| macOS | `inneragents-bridge-macos.pkg` |
| Linux (x86_64) | `inneragents-bridge-linux-amd64.deb` |
| Linux (ARM64) | `inneragents-bridge-linux-arm64.deb` |
| Windows | `inneragents-bridge-windows-amd64-setup.exe` |

These installers are unsigned — each OS will show a security warning on first launch (Gatekeeper on macOS, SmartScreen on Windows, unauthenticated package on Linux). This is expected; the install screen in the extension (Settings > Bridge) walks through the steps for each platform.
