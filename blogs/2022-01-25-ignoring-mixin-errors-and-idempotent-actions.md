---
title: "Ignoring Mixin Errors and Idempotent Actions"
url: "https://porter.sh/blog/ignoring-errors/"
date: "2022-01-25"
author: ""
feed_url: "https://porter.sh/blog/index.xml"
---

Previously, if you needed to handle an error in a bundle, you had to switch from Porter’s declarative mixin syntax to a bash script. But not anymore! The exec mixin has just added support for determining if the error returned by a command is fatal, and should stop the bundle, or if the error can be ignored. A common scenario for ignoring errors is during the install action. When an install fails halfway through, the user will try again by repeating the install command. If a resource was created...
