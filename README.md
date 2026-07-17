# rigsmith scoop bucket

Windows [Scoop](https://scoop.sh) bucket for the [RigSmith](https://rigsmith.dev)
toolchain — `rig`, `changerig`, `shiprig`, and `clauderig` in one package.

```powershell
scoop bucket add rigsmith https://github.com/rigsmith/scoop-bucket
scoop install rigsmith
```

The `rigsmith` manifest installs all four binaries from the combined
`rigsmith_<version>_windows_<arch>.zip` release archive and self-updates via
`scoop update`. Manifests here are published automatically by GoReleaser on each
release of [rigsmith/rigsmith](https://github.com/rigsmith/rigsmith).
