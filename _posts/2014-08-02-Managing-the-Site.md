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

## Liquid Crash Course

The following link contains a comprehensive course in everything available in Liquid.
The standard library is also available in Jekyll.

<http://github.com/Shopify/liquid/wiki/Liquid-for-Designers>

## Liquid Extensions Provided With Jekyll

Jekyll introduces a few other filters and tags as outlined here:

<http://github.com/mojombo/jekyll/wiki/Liquid-Extensions>
