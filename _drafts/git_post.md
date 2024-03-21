---
layout: post
title:  "Struggling to have code syncing between dev and prod environment?"
date:   2023-06-19 09:03:46 +0800
categories: git
---
During my early career in software development, We often had issues to sync a codebase between dev and production environment.
It really stressing because there can be no issue when we merge to dev but got conflict when merge to prod
There is some behaviour difference as well. Like a bug could happen only in prod but not replicable in dev env

We had few iteration of process to fix this issue. Some process are too complex involving cherry-picking and prone to human error
Until we have current git process that stayed with us from 2 years ago until now
The only command you need are rebase and merge.
It might be hard to adapt to it at first. But trust me, once you got it, It will relieve your git struggle by a lot


We have 3 environment

No.| Env Name | Usage                                                                             
1. | alpha    | Used by dev for testing                                                          
2. | beta     | Used by FE dev, QA or product team for testing (Should be more stable than alpha)
3. | prod     | Production Environment (The most stable)                                         







