---
title: PCI(e) Passthrough
url: https://pve.proxmox.com/mediawiki/index.php?title=PCI(e)_Passthrough&diff=12575&oldid=12094
date: '2026-05-21'
author: Api
feed_url: https://pve.proxmox.com/mediawiki/index.php?title=Special:RecentChanges&feed=atom
---
← Older revision Revision as of 20:33, 21 May 2026 Line 134: Line 134: update the initramfs again and update the initramfs again and reboot after that. reboot after that. Should this not work, you might need to set a soft dependency to load the gpu Should this not work, you might need to set a soft dependency to load vfio-pci modules before loading vfio-pci . This can be done with the softdep flag, see before loading the GPU modules . This can be done with the softdep flag, see also the manpages on modprobe.d for more information. also the manpages on modprobe.d for more information. For example, if you are using drivers named &lt;some-module&gt;: For example, if you are using drivers named &lt;some-module&gt;:
