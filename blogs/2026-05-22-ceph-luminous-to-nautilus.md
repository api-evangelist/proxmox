---
title: Ceph Luminous to Nautilus
url: https://pve.proxmox.com/mediawiki/index.php?title=Ceph_Luminous_to_Nautilus&diff=12586&oldid=11657
date: '2026-05-22'
author: L.Leahu-Vladucu
feed_url: https://pve.proxmox.com/mediawiki/index.php?title=Special:RecentChanges&feed=atom
---
Update links to contain information regarding archive CDNs ← Older revision Revision as of 12:56, 22 May 2026 Line 61: Line 61: == Preparation on each Ceph cluster node == == Preparation on each Ceph cluster node == Old releases must use [https://forum.proxmox.com/threads/new-archive-cdn-for-end-of-life-eol-releases.178957/ the archive CDN for Proxmox] and [https://www.debian.org/distrib/archive for Debian], so make sure that all repositories in <code>/etc/apt/sources.list</code> and <code>/etc/apt/sources.list.d/*.list</code> use: * <code>archive.debian.org</code> instead of <code>*.debian.org</code> * <code>archive.proxmox.com</code> instead of <code>*.proxmox.com</code> * In case certificate errors occur while running <code>apt-get update</code>, use HTTP instead of HTTPS for the repositories. Change the current Ceph repositories from Luminous to Nautilus. Change the current Ceph repositories from Luminous to Nautilus. Line 67: Line 72: Your /etc/apt/sources.list.d/ceph.list should look like this Your /etc/apt/sources.list.d/ceph.list should look like this deb http:// download .proxmox.com/debian/ceph-nautilus buster main deb http:// archive .proxmox.com/debian/ceph-nautilus buster main == Set the 'noout' flag == == Set the 'noout' flag ==
