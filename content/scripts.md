---
eleventyNavigation:
  parent: Get started
  key: Scripts
  order: 3

bricks:
  - path: https://raw.githubusercontent.com/anyblades/buildawesome-kit/refs/heads/main/kit/scripts/README.md
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
