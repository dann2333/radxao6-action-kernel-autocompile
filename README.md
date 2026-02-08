# radxao6-action-kernel-autocompile

This repository builds Orion O6 kernel Debian packages using
[`radxa-repo/bsp`](https://github.com/radxa-repo/bsp). The workflow runs on
published releases and uploads the resulting debs to the release. Build output
is also staged under `out/linux` and uploaded as a workflow artifact.
