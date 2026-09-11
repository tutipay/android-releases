# Noebs wallet Android downloads

Signed Android APKs for the Noebs wallet synthetic Mojaloop demo.

[Download version 26.09.11-alpha.2](https://github.com/tutipay/android-releases/releases/tag/v26.09.11-alpha.2)

Choose **ARM64** for a recent Samsung or other ARM64 phone. Choose **universal** if you are unsure. Android 7.0 or newer is required.

1. Download the APK and open it on your phone. Allow installation from that download source if Android asks.
2. Open the app, choose **Noebs wallet**, and continue with Google.
3. Complete authenticator enrollment if prompted. Ask the demo organizer to enable your Google account for the demo; each tester receives a separate wallet.

This alpha uses synthetic SDG. Wallet access, a registered wallet alias and demo funding are provisioned separately from installation. The demo organizer must complete these before payment testing. Keep authenticator setup keys and one-time codes on your own device.

The APKs use the existing demo signing certificate and update the previous signed Mojaloop alpha without uninstalling it. This is the debuggable demo build, not a Play production release. The application ID is `com.tutipay.app.alpha`.

Each release includes `SHA256SUMS` and `release-manifest.json` with artifact hashes, the signing certificate fingerprint, version and validation results. Source code and signing material are maintained separately in the private application repository; this repository contains download documentation and release assets only.
