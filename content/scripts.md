---
eleventyNavigation:
  parent: Core
  key: Scripts

title: <mark><i class="fa-brands fa-square-build-awesome-stroke fa-width-auto"></i> Kit</mark> Scripts
bricks:
  - path: https://raw.githubusercontent.com/anyblades/buildawesome-kit/refs/heads/main/core/scripts/README.md
---

---

## More

### Find and kill <small>11ty processes</small>

```sh
ps aux | grep eleventy
pkill -f eleventy
```

You can even combine it with other processes hanging around:

```sh
ps aux | grep -E 'eleventy|tailwind|.bin/serve'
pkill -f tailwind
pkill -f .bin/serve
```
