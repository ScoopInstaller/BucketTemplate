# Scoop Bucket Template

<!-- Uncomment the following line after replacing placeholders -->
<!-- [![Build Status](https://ci.appveyor.com/api/projects/status/<appveyor-badge-id>?svg=true)](https://ci.appveyor.com/project/<username>/<bucketname> "Build Status") [![Excavator](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml/badge.svg)](https://github.com/<username>/<bucketname>/actions/workflows/excavator.yml) -->

Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

How do I install these manifests?
---------------------------------

To add this bucket, run `scoop bucket add <bucketname> https://github.com/<username>/<bucketname>`. To install, do `scoop install <manifest>`.

How do I contribute new manifests?
----------------------------------

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).

----

#### To use this template

- Modify the Readme.md and the bin/auto-pr.ps1 files accordingly.
- Enable GitHub Actions for this repository.
- Login to AppVeyor and import this repository.
