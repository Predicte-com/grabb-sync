# Grabb Sync — builds

Public release repo for **Grabb Sync** (Windows tray app for QuickBooks Web Connector).

Source code lives in [`Predicte-com/grabb-qbd-connector`](https://github.com/Predicte-com/grabb-qbd-connector).

## Download

See [Releases](https://github.com/Predicte-com/grabb-sync/releases).

| Asset | Use |
|---|---|
| `GrabbSyncSetup.exe` | Preferred installer (Inno Setup) |
| `Grabb.Sync.exe` | Portable exe (no installer) |

## For Grabb ops

After each publish, set on `qbwc.grabb.ai`:

```env
GrabbSync__LatestVersion=1.0.0
GrabbSync__DownloadUrl=https://github.com/Predicte-com/grabb-sync/releases/download/v1.0.0/GrabbSyncSetup.exe
```

(Use `Grabb.Sync.exe` in the URL if only the portable build was uploaded.)
