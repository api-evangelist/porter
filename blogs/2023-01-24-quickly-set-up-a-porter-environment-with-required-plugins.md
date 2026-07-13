---
title: "Quickly set up a Porter environment with required plugins"
url: "https://porter.sh/blog/install-multiple-plugins/"
date: "2023-01-24"
author: ""
feed_url: "https://porter.sh/blog/index.xml"
---

Breaking change The recent porter v1.0.5 release introduced a new flag --file on porter plugins install command. Its intention is to allow users to install multiple plugins through a plugins definition file with a single porter command. However, it did not work as expected due to bad file format. The fix that contains the correct schema has been published with a new v1.0.6 release. If you have an existing plugins file, please update it to work with v1.0.6+. Install multiple plugins with a...
