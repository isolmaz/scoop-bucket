# SSDownload Scoop bucket

[Scoop](https://scoop.sh) manifest of [SSDownload](https://github.com/isolmaz/SSDownload), a native Windows file, video and audio download manager.

```powershell
scoop bucket add isolmaz https://github.com/isolmaz/scoop-bucket
scoop install isolmaz/ssdownload
```

Scoop installs the portable copy, registers the browser connection for it and adds the `ssdownload` command. `scoop update ssdownload` updates it. Quit SSDownload before `scoop update` or `scoop uninstall`, because Scoop skips the app while it runs. `scoop uninstall` hands the browser connection back to a copy installed with Setup.

`bucket/ssdownload.json` is written for each release by `scripts/package-managers.ps1` in the SSDownload repository. Report problems in the [SSDownload issues](https://github.com/isolmaz/SSDownload/issues).
