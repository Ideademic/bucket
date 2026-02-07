# Ideademic Scoop Bucket

A [Scoop](https://scoop.sh) bucket for Ideademic packages on Windows.

## Installation

### Add the bucket, then install by name

```powershell
scoop bucket add ideademic https://github.com/Ideademic/bucket
scoop install <app-name>
```

### Or install directly without adding the bucket first

```powershell
scoop install https://raw.githubusercontent.com/Ideademic/bucket/main/bucket/<app-name>.json
```

## Manifests

App manifests live in the [`bucket/`](bucket/) directory.
