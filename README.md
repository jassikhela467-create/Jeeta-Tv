# Jeeta TV

A client/player for IPTV services that the user is authorized to access.

## Current implementation
- M3U/M3U8 remote playlists
- Multiple saved providers
- Xtream Codes live-stream discovery
- Compatible Stalker/Portal-MAC live-channel discovery (provider implementations can vary)
- Media3/ExoPlayer playback
- Channel search
- Favorites persisted with Room
- Watching history persisted with Room
- Home/live/movies/series/favorites navigation
- Android 7.0+ (minSdk 24)
- GitHub Actions workflow that builds a release APK without Android Studio

## Build the APK from a phone
1. Create a GitHub account if needed.
2. Create a new repository, e.g. `JeetaTV`.
3. Upload all files/folders from this project, including `.github/workflows/build-apk.yml`.
4. Open the repository's **Actions** tab.
5. Select **Build Jeeta TV APK**.
6. Tap **Run workflow** (or push to `main` to trigger it).
7. Wait for the green successful run.
8. Open the completed run and scroll to **Artifacts**.
9. Download `JeetaTV-release-apk` and extract the APK.
10. On Android, allow installation from that file manager/browser when prompted, then install.

## Important
This app does not include channels, subscriptions, credentials, or pirated sources. Enter only playlist/provider details you are entitled to use. Portal/MAC services can differ, so some providers may require adapter adjustments.
