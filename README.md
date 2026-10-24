# DOWNLOAD-NXT

Official static download landing page for **NXT UI**, a custom Android TV launcher.

## Website

After enabling GitHub Pages (Settings → Pages → Deploy from a branch → main /root), visit:

https://anirudhadebbarma031214-commits.github.io/DOWNLOAD-NXT/

## How downloads work

The website requests the latest published release in [NXT-UI](https://github.com/anirudhadebbarma031214-commits/NXT-UI/releases) and links directly to the first .apk asset. If no release APK exists, it shows a clear message and opens the releases page instead of offering a broken APK link.

**Note:** A successful GitHub Actions run creates an artifact, not necessarily a GitHub Release. Publish an APK as a release asset to enable one-click downloads for everyone.

## Publishing an APK

1. Build and test an APK in NXT-UI Actions.
2. Open NXT-UI → Releases → Draft a new release.
3. Create a tag (e.g. v1.0.0), upload the APK, and publish.
4. This download website will automatically detect the release.
