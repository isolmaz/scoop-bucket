# SSDownload Scoop bucket

[Scoop](https://scoop.sh) manifest of [SSDownload](https://github.com/isolmaz/SSDownload), a native Windows file, video and audio download manager.

```powershell
scoop bucket add isolmaz https://github.com/isolmaz/scoop-bucket
scoop install isolmaz/ssdownload
```

Scoop installs the portable copy, registers the browser connection for it and adds the `ssdownload` command. `scoop update ssdownload` updates it; quit SSDownload first, because Scoop skips an update while it runs.

`bucket/ssdownload.json` is written for each release by `scripts/package-managers.ps1` in the SSDownload repository. Report problems in the [SSDownload issues](https://github.com/isolmaz/SSDownload/issues).
