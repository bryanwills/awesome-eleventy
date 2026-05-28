---
eleventyNavigation:
  key: Filters
  order: 5
description: A collection of useful Eleventy filters for Nunjucks/Liquid via Eleventy Blades plugin.
revised: 2026-03-24

bricks:
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/attr_concat.js
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/attr_includes.js
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/attr_set.js
  - path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/date.js
    sections: [docs, code]
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/fetch.js
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/if.js
  - md: |-
      ### `markdownify`
      ```js
      eleventyConfig.addFilter("markdownify", (content) => md.render(String(content ?? "")));
      ```
      Living example: https://github.com/anyblades/eleventy-blades/blob/main/packages/eleventy-blades-base/eleventy.config.js
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/merge.js
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/remove_tag.js
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/section.js
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/strip_tag.js
  - sections: [docs, code]
    path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/filters/unindent.js
  # - md: |-
  #     ---
  #     ## Install
  # - md: "###### <mark>Via plugin</mark>"
  # - teaser: /
  #   no_toc: true
  # - md: "###### <mark>Included with</mark>"
  # - teaser: /starters/
  #   no_toc: true
---
