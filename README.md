# Scoop bucket for Statac

Statac is a friendlier static site generator for personal websites. This
bucket installs its ready-built binary on Windows (x86-64).

```powershell
scoop bucket add statac https://git.statac.dev/statac/scoop-statac
scoop install statac
```

Later, `scoop update statac` brings the newest version.

The manifest is `bucket/statac.json`. It downloads the package from
`https://get.statac.dev` and checks it against the SHA-256 written in the
manifest.

The bucket's home is `https://git.statac.dev/statac/scoop-statac`. The
copy at `https://github.com/statac-ssg/scoop-statac` is read-only, and a
bucket added from it keeps working. Statac's source, documentation and
issues are at `https://git.statac.dev/statac/statac`, not here.
