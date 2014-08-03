---
layout: post
category : Overview
tags : [instructions]
description: |
  How to set up a file for this system.
---

How to add a new file.

There was a submodule thing going on with github.  Tried this:

    git submodule update --init
    
Evidently, the submodule is a repository within a repository.  I didn't need the `_theme_packages` directory, which seems to have been the source of the problem.  So, I deleted it.
