---
title: ''
featured_image: ''
omit_header_text: true
description: ''
type: page

---

```
## Getting Started with hatchery Linux

wget -c https://iso.hatcherylinux.org/gila-080626-amd64.hybrid.iso

dd the iso or etcher it ..


## Verifying the ISO

wget -c https://iso.hatcherylinux.org/gila-080626-amd64.hybrid.iso.sha512sum.asc

gpg --keyserver keyserver.ubuntu.com --recv-keys 3f057386f99e3151

gpg --verify gila-080626-amd64.hybrid.iso.sha512sum.asc

sha512sum -c gila-080626-amd64.hybrid.iso.sha512sum.asc
```
