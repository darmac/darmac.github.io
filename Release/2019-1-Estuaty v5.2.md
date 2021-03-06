---
layout:     post
author:     Estuary
header-img: img/post-bg-hacker.jpg
catalog: true
tags:
    - Releases
---
<h2><strong>Release Information:</strong></h2>
<a href="https://open-estuary.github.io/2015/11/16/binary-download/"target="_blank"><u>Please click here to go to the download 
page of this release</u></a>
<pre>Release Version         : 5.2
Release Date            : 20-Jan-2019
Application support     : https://github.com/open-estuary/distro-repo/blob/master/docs/packages_list_5.2.md
   CI                   : Support NFS/PXE boot testing on D05/D06 boards CentOS & Debian
   Armor tools          : include malluma, perf, gdb, strace... 
Distributions Supported : CentOS 7.5,Debian 9,mini-rootfs 1.1
Kernel Version          : 4.19.5
Bootloader Info         : 
   TaiShan2280          : UEFI 1.58 + Grub 2.02-beta3
   D06                  : UEFI 3.03 + Grub 2.02-beta3
Boot mode               : PXE, NFS, iBMC Load ISO
Boards Supported        : D05(ARM64), D06(ARM64)
Deployment Methods      : Auto ISO file load, PXE</pre>
<h2><strong>Introduction:</strong></h2>
Estuary is a development version of the whole software solution which target is the ICT market. It is a long term solution and focus on the combination of the high level components. It is expected to be re-based to top tip kernel /distribution versions/applications at the earliest.
<h2><strong>Changelog</strong>:</h2>
<pre>1. UEFI
       - Fix some bugs
       - Upgrade M7 firmware
  2. OS
       - Upgraded Linux kernel version to v4.19.5
  3. Distros
       - N/A
  4. Applications
       - Added benchmark tools : speccpu2006, Hibench
       - Added virtualization tools : docker
       - Added big data tools : hadoop, hive, spark
       - Added other tools : ltp, busybox, boost1.63, ceph   
  5. Armor tools
       - Upgraded profiling tool : Malluma2.0, bcc-tools     
  6. Deployment
       - Support standard network installation, ISO installation, and compatible with the original NFS deployment
       - Build scripts support parallel compiling of CentOS, Debian and common modules     
  7. Document
       - Updated project documentation (Readme, Grub, deploy_manual,etc)
  8. CI/Automation
       - Supported basic CI/Automation for D05 (Build, NFS/PXE Deployment, Some tests)
       - Supported basic CI/Automation for D06 (Build, NFS/PXE Deployment, Some tests)</pre>
  <h2><b>Known issues</b>:</h2>
  <pre>1. After upgrade the bios,cannot find the option to boot CentOS & Debian</pre>
  
