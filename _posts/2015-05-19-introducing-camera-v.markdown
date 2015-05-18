---
layout: post
title:  "Introducing Camera-V"
date:   2015-05-19 16:46:59
categories: how-to
---

## 1. Extracting J3M metadata from images, video, and logs

This is the most basic way to start browsing j3m metadata.  Using the [Camera-V extraction utility](https://github.com/harlo/CameraVExpress), easily export your data to json and csv format.

<iframe width="560" height="315" src="https://www.youtube.com/embed/R016Of8fCqg" frameborder="0" allowfullscreen></iframe>

## 2. Auditing J3M metadata

If you'd like to do things like check a file's provenance, run queries over metadata, and make those capabilities public, check out the [Camera-V Core suite](https://github.com/harlo/InformaFrontend).  This is EXTREMELY experimental software, and has not gone through any auditing.  But good news, it will be!  Over the next few months, this project will grow into something much more stable and usable.  Here's a demo of what's in store.

## 3. Notarizing J3M metadata

If you have access to a j3m notary server (see above), you can also notarize your media using the [Camera-V notary tool](https://github.com/harlo/camera-v.notary).