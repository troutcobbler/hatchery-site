---
title: ''
featured_image: ''
omit_header_text: true
description: ''
type: page

---

```
## Getting Started with hatchery Linux

wget -c https://iso.hatcherylinux.org/pecos-072123-amd64.hybrid.iso

dd the iso or etcher it ..


## Verifying the ISO

wget -c https://iso.hatcherylinux.org/pecos-072123-amd64.hybrid.iso.sha512sum.asc

gpg --keyserver keyserver.ubuntu.com --recv-keys 3f057386f99e3151

gpg --verify pecos-072123-amd64.hybrid.iso.sha512sum.asc

sha512sum -c pecos-072123-amd64.hybrid.iso.sha512sum.asc
```
