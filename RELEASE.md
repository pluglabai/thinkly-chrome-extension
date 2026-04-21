# Beta Preview Release Checklist

1. Create or update branch: `beta-preview`
2. Commit the preview scaffold files on that branch
3. Create or update prerelease tag: `chrome-extension-beta-v4.1.0-beta.1`
4. Publish a GitHub prerelease with:
   - screenshots and docs at minimum
   - optional installable beta ZIP only if it was generated with a separate beta key and separate beta Google OAuth client
   - release notes pointing users to the stable branch for default installs
5. Verify README clearly states this branch is preview-only
