# gzip

GNU gzip 1.13: gzip, gunzip, zcat

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install gzip
```

| | |
|---|---|
| Version | 1.13 |
| Licence | GPL-3.0-or-later |
| Upstream | - |
| Needs | [`bash`](https://github.com/Artfical/tpkg-bash) |
| Needs tOS build | 619 or newer |
| Size | 71674 bytes (142209 unpacked) |
| SHA-256 of the `.tpkg` | `090be7ac32b1c9fb3c10c1b38d112c385109732ce3118885c0476407c76837e6` |

## Commands it adds

| Command | Runs |
|---|---|
| `gunzip` | `bin/gunzip` |
| `gzexe` | `bin/gzexe` |
| `gzip` | `bin/gzip` |
| `uncompress` | `bin/uncompress` |
| `zcat` | `bin/zcat` |
| `zcmp` | `bin/zcmp` |
| `zdiff` | `bin/zdiff` |
| `zegrep` | `bin/zegrep` |
| `zfgrep` | `bin/zfgrep` |
| `zforce` | `bin/zforce` |
| `zgrep` | `bin/zgrep` |
| `zless` | `bin/zless` |
| `zmore` | `bin/zmore` |
| `znew` | `bin/znew` |

## Download

The package file (`gzip-1.13.tpkg`) and the sources it was built from are the assets of the
[v1.13 release](https://github.com/Artfical/tpkg-gzip/releases/tag/v1.13).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `gzip-1.13.tar.xz`

Check a download: `sha256sum gzip-1.13.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: GPL-3.0-or-later. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
