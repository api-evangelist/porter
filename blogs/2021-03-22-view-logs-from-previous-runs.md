---
title: "View Logs From Previous Runs"
url: "https://porter.sh/blog/save-logs/"
date: "2021-03-22"
author: ""
feed_url: "https://porter.sh/blog/index.xml"
---

With the v0.35.0 release of Porter , the logs generated when install/upgrade/invoke/uninstall is run are persisted. Now you can view logs from previous runs, which can come in handy when troubleshooting a deployment. You can view the logs from the most recent execution of a bundle with the porter logs command: $ porter logs -i whalegap executing install action from whalegap (installation: whalegap) Install WhaleGap /usr/local/bin/helm helm install --name whalegap ./charts/whalegap --replace...
