---
title: How to commit oVirt DWH change
category: howto
authors: quaid, yaniv dary
wiki_category: How to
wiki_title: How to commit oVirt DWH change
wiki_revision_count: 2
wiki_last_updated: 2012-03-22
---

<!-- TODO: Content review -->

# How to commit oVirt DWH change

Export project from TOS. Replace files that you changed in path:

      < repository folder path >/ovirt-dwh/data-warehouse/history_etl/tos_project

with the files from the export. Then rebase the commit.

## Note

Please do not send patches with java changes. Only moderators can export and commit java changes.

[Category:How to](Category:How to)
