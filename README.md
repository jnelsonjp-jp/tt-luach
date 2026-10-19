# TT Luach releases

Signed Windows and Linux application releases for Tzemach Tzedek Community Centre, Bondi, Australia.

This is an **updates-only repository**. Shul settings, notices, study libraries, administrator keys, signing keys and application source code are not published here.

Install the complete bootstrap package supplied privately for initial setup. The release assets here are **binary-only updates**, not complete standalone installers. Version 0.2.0 introduces **Admin → Remote & updates**. Later updates can be checked and installed there, locally or through private Tailscale Serve access. App updates require the luach administrator key, a valid pinned publisher signature and the matching binary checksum. Existing data and settings are preserved.

Release channel:
`https://github.com/jnelsonjp-jp/tt-luach/releases/latest/download/update-manifest.json`

The Windows build is cross-compiled and still needs acceptance testing on Windows hardware. The Raspberry Pi/ARM build is not available yet. This is a review build; festival parashah coverage, memorials and the remainder of the original-program migration are pending.

The unsigned Windows bootstrap installer may require your organization's approval. The updater's Ed25519 release signature is separate from Windows Authenticode signing. Dependency licenses accompany the release.
