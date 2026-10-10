# Scoop bucket for Statac

Statac is the friendly static site generator. This bucket installs its
ready-built binary on Windows (x86-64).

```powershell
scoop bucket add statac https://github.com/statac-ssg/scoop-statac
scoop install statac
```

Later, `scoop update statac` brings the newest version.

The manifest is `bucket/statac.json`. It downloads the package from the
releases of `https://github.com/statac-ssg/statac` and checks it against
the SHA-256 written in the manifest. Statac's source, documentation and
issues are in that repository, not this one.
