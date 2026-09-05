# DuckWeights desktop releases

Public distribution for DuckWeights: installers, signed update artifacts, checksums, and release notes. Application source is maintained separately and is not published here.

No official desktop release has been published yet. Initial candidates target Ubuntu 24.04 x86-64 and macOS 13+ on Apple Silicon and Intel. Windows installers remain experimental and are not currently distributed.

## Downloads and verification

Use the Releases page when packages become available. Each release will include architecture-specific installers, updater signatures, SHA256SUMS, and desktop-update.json. Mac release apps require Developer ID signing and Apple notarization. Linux update signatures authenticate the publisher; they are not an operating-system certificate.

The updater.pub file is the base64-encoded Tauri update verification public key. It is public by design and cannot sign software. Never submit private keys or account credentials to this repository.

Prereleases are for manual testing. The stable update channel reads the latest non-prerelease. A draft is not a published or certified release.
