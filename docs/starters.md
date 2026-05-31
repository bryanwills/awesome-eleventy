---
eleventyNavigation:
  parent: Get started
  key: Starter projects
  order: 11
content_for_header: |-
  <style>
    td a:has(> i) { text-wrap: balance }
    td code { padding: 0.25em }
    td > code { font-size: x-small; vertical-align: middle }
  </style>
revised: 2026-04-24
=== CONTENT: ===
title: Minimal <i class="fa-brands fa-eleventy"></i> starters <sub>as of May 2026</sub>
description: |-
  Eleventy ecosystem offers a [wide variety of starters](/awesome/#more-starters).

  Not sure where to begin? Start with a minimal template:
bricks:
  - path: ./_starters.md
  - md: ---
---

### Minform starter

<blockquote>

Minform v0.3.1 released at https://github.com/johnheenan/minform which will work with formsubmit.io above to convert forms to email. This is the Hostfurl independent version of Minformhf.

To work with formsubmit.io the following edits are required in `_data/site.yml`:

```
nohtmx: true
corsprod: true
corsurl: https://formsubmit.co
formpath: /somearbitrarycharacters
```

Demo at https://minform.hostfurl.com

<cite>https://discord.com/channels/741017160297611315/1494619630273298504/1495806652396601444</cite>

</blockquote>
