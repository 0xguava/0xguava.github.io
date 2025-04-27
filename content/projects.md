---
author : ' '
title : 'Projects'
ShowShareButtons : false
ShowReadingTime : false
ShowPostNavLinks : false
ShowBreadCrumbs : true
disableShare : true
showToc: true 
Tocopen: true
---

{{< gitrepocard url="https://github.com/0xguava/auto-install" name="0xguava/auto-install"
description="Creating unattended installation ISO for the mighty Archlinux" language="bash" forks="1" stars="1" >}}

This project aims to create a **custom**, **minimal** ISO image for **unattended installation** of [Archlinux](https://archlinux.org)
without using net-boot, cloud-init or any other similar technology.

- ISO is created and released *(with version tag)* by Github Workflow. Instructions for creating ISO are in `buildiso.sh`,
which is executed by Github Workflow.

- Configurations and user credentials are read from `config.json` and installation is performed by `arch.sh` in live ISO environment.

**Demo video**: 

---
