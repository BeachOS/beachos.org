---
title: BeachOS Production builds
nav_title: Production
redirect_from:
    - /contribute/build/production/
    - /development/build/production/
---

The official BeachOS releases are built on our official build server running Debian Stable (buster/10 at time of writing)

They're `user` builds, and we build `target-files-package otatools-package`, and then copy those zips to a dedicated offline signing machine to sign and release.