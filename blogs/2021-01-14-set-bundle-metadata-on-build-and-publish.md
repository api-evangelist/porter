---
title: "Set Bundle Metadata on Build and Publish"
url: "https://porter.sh/blog/ci-flags/"
date: "2021-01-14"
author: ""
feed_url: "https://porter.sh/blog/index.xml"
---

With the v0.31.0 release of Porter you can now quickly set metadata on your bundle. This corrects confusing terms around the OCI reference of the bundle (the location of a bundle in a registry). reference = registry/name:tag Reference : A bundle reference is the location of a published bundle. For example, ghcr. io /getporter/porter/porter-hello:v0.1.1 . Previously this was called bundle tag. Until we release v1.0, Porter detects when you use the flags with the old meanings and fixes it for...
