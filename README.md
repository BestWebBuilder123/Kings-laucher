# Kings Launcher — Android companion

This repository contains an Android app project inspired by the Kings Launcher desktop screenshots.

## Build an installable APK

Every push to `main` starts the **Build Kings Launcher APK** GitHub Actions workflow.

1. Open the repository's **Actions** tab.
2. Open the latest **Build Kings Launcher APK** run.
3. Wait for the run to finish successfully.
4. Under **Artifacts**, download `Kings-Launcher-debug-apk`.
5. Open the downloaded artifact archive and install `app-debug.apk` on your Android device.

You can also start a build manually from Actions → Build Kings Launcher APK → Run workflow.

## Current Android scope

- Mobile interface inspired by the desktop Home, Discover, My Games, Continue Playing, Favorites, FastFlags, Flag Editor, Profile, and Recorder pages.
- Local game library, favorites, history, flag JSON editor/import/export, preferences, and moment notes.
- Game launch handoff to the Roblox Android app using a Roblox experience link.

## Platform limitations

This is an Android companion, not a binary conversion of the Windows installer. Android apps cannot directly edit the Windows Roblox client's private settings file, detect a Windows Roblox process, capture a Windows application window, or provide the same Windows rolling replay buffer. The current build keeps those areas visible and explains the limitation. Live Roblox catalog/profile lookup and cloud sync are not connected yet.

The first APK is a debug-signed test build. A separate, privately stored signing key is needed for stable release updates.