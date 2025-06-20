---
title: Website Notes
modified: Friday 20th June 2025 22:36:29
date: 2025-06-20
showDate: "false"
draft: "false"
showPagination: "false"
---
## Obsidian Git not pushing successfully

It was a Git problem with some of the bigger files, images, etc. I just did this and it worked: 

```
git config --global http.postBuffer 1048576000
```
