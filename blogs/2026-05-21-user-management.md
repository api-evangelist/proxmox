---
title: User Management
url: https://pve.proxmox.com/mediawiki/index.php?title=User_Management&diff=12574&oldid=12311
date: '2026-05-21'
author: Api
feed_url: https://pve.proxmox.com/mediawiki/index.php?title=Special:RecentChanges&feed=atom
---
← Older revision Revision as of 20:33, 21 May 2026 Line 47: Line 47: Separated privileges: The token needs to be given explicit access with ACLs. Separated privileges: The token needs to be given explicit access with ACLs. Its effective permissions are calculated by intersecting user and token Its effective permissions are calculated by intersecting user and token permissions. permissions . This is the default for newly created tokens . Full privileges: The token&#8217;s permissions are identical to that of the Full privileges: The token&#8217;s permissions are identical to that of the associated user. associated user. Disable Privilege Separation only when the integration genuinely needs the user&#8217;s full permissions. Set an expire timestamp (Unix epoch seconds) when creating a token so that abandoned automation does not silently keep working. The authentication code refuses requests once the deadline has passed. The token value is only displayed/returned once when the token is The token value is only displayed/returned once when the token is generated. It cannot be retrieved again over the API at a later time! generated. It cannot be retrieved again over the API at a later time!
