# Bop for Windows release host

This repository hosts Bop's Windows installers, portable packages, checksums and RSA-signed update manifests. Application source is maintained separately.

Verified downloads will appear on the Releases page. Each installer includes the .NET runtime and uses per-user installation. A Bop license is required; it covers two computers in total across macOS and Windows.

The application verifies update metadata and installer integrity before installation. The manifest signing key is not stored in this repository. The public key is bundled with Bop.

Windows Authenticode signing and manual device acceptance are reported per build in the release notes; do not infer them from the update manifest signature.
