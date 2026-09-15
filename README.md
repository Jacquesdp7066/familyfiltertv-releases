# familyfiltertv-releases

Release assets for [FamilyFilterTV](https://jacquesdp7066.github.io/familyfiltertv-site/) — the
source repository is private.

This repo holds nothing but GitHub Releases: signed direct-install APKs published by the app's
`direct-release.yml` CI workflow on each tagged version, plus their `.sha256` checksums. Each
release carries a versioned asset (`FamilyFilterTV-<version>-direct.apk`) and a stable-named copy
(`FamilyFilterTV-direct.apk`) at `releases/latest/download/FamilyFilterTV-direct.apk`, so the app
and the website can always point at the newest build without knowing its version number in advance.
