---
title: "A more YAML friendly template delimiter"
url: "https://porter.sh/blog/new-template-delimiter/"
date: "2022-07-26"
author: ""
feed_url: "https://porter.sh/blog/index.xml"
---

Porter is getting a different template delimiter in v1! Previously, the template delimiter used in porter.yaml was {{ }} and we are changing it to ${ } starting in v1.0.0-beta.2. What does this change? The problem with the old delimiter is that it forced all templates to be wrapped in quotes because curly braces are special characters in YAML. The quotes made it impossible to pass a boolean or numeric value to a mixin because the wrapping quotes always forced the value to be a string....
