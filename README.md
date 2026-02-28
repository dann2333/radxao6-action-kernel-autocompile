This repository provides a GitHub Actions workflow to build Radxa Orion O6 kernel .deb packages from https://github.com/radxa-pkg/linux-sky1 and publish them as a GitHub Release.

Run the "Build Orion O6 Kernel Debs" workflow via workflow_dispatch. The optional release_tag input lets you override the release tag; otherwise it uses orion-o6-kernel-<version>-<utc-build-date> (for example, orion-o6-kernel-6.6.89-3-20260228-174048).
