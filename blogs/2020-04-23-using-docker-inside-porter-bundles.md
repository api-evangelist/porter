---
title: "Using Docker inside Porter Bundles"
url: "https://porter.sh/blog/using-docker-in-bundles/"
date: "2020-04-23"
author: ""
feed_url: "https://porter.sh/blog/index.xml"
---

Sometimes you need a hammer, and that hammer happens to be a whale 🐳. We all use containers as part of our pipeline: building images, running a one-off command in a utility container, spinning up a test environment to verify your application, or even more creative tasks that you have already containerized. Well now you can reuse all that hard work and logic from within your bundles! Let’s walk through using my favorite container, ghcr.io/getporter/examples/images/whalesay , in a bundle....
