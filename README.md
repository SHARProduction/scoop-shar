# SHAR Production Scoop Bucket

This public Scoop bucket distributes small, local production-workflow tools by
[SHAR Production](https://sharprod.com/), an AI-hybrid video production studio.

## Add the bucket

```powershell
scoop bucket add shar https://github.com/SHARProduction/scoop-shar
scoop install production-metadata-linter
```

The first package is `production-metadata-linter`: a local, rights-aware JSON
manifest validator. It has no API token, service account or network requirement
after download. Code and documentation are MIT.

Each manifest points to a versioned GitHub Release asset and locks its
SHA-256. The workflow in this repository performs a Windows installation and
CLI smoke test for every change.
