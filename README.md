# Grabb Sync — builds

Public release repo for **Grabb Sync** (Windows tray app for QuickBooks Web Connector).

Source code: [`Predicte-com/grabb-qbd-connector`](https://github.com/Predicte-com/grabb-qbd-connector).

## Download

See [Releases](https://github.com/Predicte-com/grabb-sync/releases).

**Only asset:** `GrabbSyncSetup.exe` (Inno Setup installer)  
Used for first install (email) **and** in-app update (`DownloadUrl`).

## Publish (Windows)

From `grabb-qbd-connector`:

```powershell
.\scripts\publish-agent.ps1
```

Upload `artifacts\GrabbSyncSetup.exe` to a new GitHub Release (tag `vX.Y.Z`).

## Server config (`qbwc.grabb.ai`)

```env
GrabbSync__LatestVersion=1.0.0
GrabbSync__DownloadUrl=https://github.com/Predicte-com/grabb-sync/releases/download/v1.0.0/GrabbSyncSetup.exe
```
