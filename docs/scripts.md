---
eleventyNavigation:
  parent: Get started
  key: Useful scripts
  order: 3

bricks:
  - path: https://raw.githubusercontent.com/anyblades/eleventy-blades/refs/heads/main/packages/do/README.md
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
