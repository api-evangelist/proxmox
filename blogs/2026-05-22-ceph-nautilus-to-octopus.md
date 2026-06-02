---
title: Ceph Nautilus to Octopus
url: https://pve.proxmox.com/mediawiki/index.php?title=Ceph_Nautilus_to_Octopus&diff=12588&oldid=12467
date: '2026-05-22'
author: L.Leahu-Vladucu
feed_url: https://pve.proxmox.com/mediawiki/index.php?title=Special:RecentChanges&feed=atom
---
Update links to contain information regarding archive CDNs ← Older revision Revision as of 13:03, 22 May 2026 Line 17: Line 17: == Preparation on each Ceph cluster node == == Preparation on each Ceph cluster node == Old releases must use [https://forum.proxmox.com/threads/new-archive-cdn-for-end-of-life-eol-releases.178957/ the archive CDN for Proxmox] and [https://www.debian.org/distrib/archive for Debian], so make sure that all repositories in <code>/etc/apt/sources.list</code> and <code>/etc/apt/sources.list.d/*.list</code> use: * <code>archive.debian.org</code> instead of <code>*.debian.org</code> * <code>archive.proxmox.com</code> instead of <code>*.proxmox.com</code> * In case certificate errors occur while running <code>apt-get update</code>, use HTTP instead of HTTPS for the repositories. Change the current Ceph repositories from Nautilus to Octopus. Change the current Ceph repositories from Nautilus to Octopus. Line 24: Line 28: Your /etc/apt/sources.list.d/ceph.list should look like this Your /etc/apt/sources.list.d/ceph.list should look like this deb http:// download .proxmox.com/debian/ceph-octopus buster main deb http:// archive .proxmox.com/debian/ceph-octopus buster main == Set the 'noout' flag == == Set the 'noout' flag ==
