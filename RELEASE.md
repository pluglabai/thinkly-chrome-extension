# Release Checklist

1. Build the private Thinkly monorepo extension package.
2. Run `npm run package:webstore`.
3. Upload `thinkly-webstore-v4.1.0.zip`.
4. Refresh `thinkly-extension.zip` with the same payload for stable website links.
5. Create or update release tag `chrome-extension-v4.1.0`.
6. Confirm the uploaded ZIP does not contain a top-level `manifest.key`.

This repository should only publish store-safe release artifacts.
