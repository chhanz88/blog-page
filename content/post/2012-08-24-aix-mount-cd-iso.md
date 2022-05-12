---
author: chhanz
categories:
- aix
date: "2012-08-24T00:00:00Z"
description: ""
tags:
- aix
title: '[AIX] Mount CD/DVD & ISO Image'
---

# [AIX] Mount CD/DVD & ISO Image
* * *

## CD 혹은 DVD 를 CLI Command 로 Mount :   
```
# mount -V cdrfs -o ro /dev/cd0 /mnt
```

## ISO Image 를 CLI Command 로 Mount :
```
# loopmount -i aix-6100-09-02-icd.iso -o "-V cdrfs -o ro" -m /mnt
```
