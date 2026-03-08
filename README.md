## 📦 Releases

This is a fork of [Nuked SC-55](https://github.com/nukeykt/Nuked-SC55) by nukeykt,
compiled natively for **Intel Macs (x86_64)**.

The original project supports Linux/macOS via SDL but does not distribute
pre-built binaries for Intel Mac. This fork provides ready-to-run builds
so you don't need to compile from source.

### Download

Go to the [Releases](../../releases) tab and download the latest `.zip` for your macOS version.

### How to create a new release (for maintainers)

1. Tag the commit before publishing:
```bash
   git tag v1.0.0-intel
   git push origin v1.0.0-intel
```
2. Go to **Releases → Draft a new release** on GitHub
3. Select the tag you just pushed (or create one inline)
4. Attach the compiled binary and publish

> ⚠️ GitHub requires a valid tag to publish a release.
> Leaving the tag field blank will throw:
> `tag name can't be blank / published releases must have a valid tag`

### Tag convention

| Tag | Meaning |
|-----|---------|
| `v1.0.0-intel` | First stable Intel Mac build |
| `v1.1.0-intel` | Based on upstream changes |
| `v1.0.1-intel` | Bug fix on existing build |
