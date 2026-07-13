---
title: "Get those secrets out of your config"
url: "https://porter.sh/blog/secret-free-config/"
date: "2022-02-01"
author: ""
feed_url: "https://porter.sh/blog/index.xml"
---

As part of the v1 hardening process, we have been hard at work securing Porter. Keeping sensitive data off your machine, and safely in a secret store or vault where it belongs is a big part of that. Now Porter’s config file is getting the same white glove treatment that bundle credentials always have! We have added templating support to Porter’s config file so that you can use environment variables and secrets without hard-coding sensitive data in the file. Porter has plugins for retrieving...
