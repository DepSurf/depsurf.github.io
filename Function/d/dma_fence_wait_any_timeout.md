# Function: <code>dma_fence_wait_any_timeout</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585307760,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:440",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585307760,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 725
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585396224,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:469",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585396224,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 717
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585825152,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:468",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585825152,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 693
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586071648,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:469",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586071648,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 702
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586216112,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:567",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586216112,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 595
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:577",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586459596,
      "name": "dma_fence_wait_any_timeout.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586458352,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586605760,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586605760,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587393904,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:554",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587393904,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 658
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587462160,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:764",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587462160,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 668
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587344112,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:845",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587344112,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 676
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587910512,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:845",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587910512,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 645
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589261232,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:843",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261232,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590823136,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:847",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590823136,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591164784,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:848",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591164784,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591510768,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:848",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591510768,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 649
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499491400,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499491400,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231964024,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231964024,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 788
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292775872,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292775872,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 872
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276707960,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276707960,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586296240,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586296240,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586137616,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586137616,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586553728,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586553728,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```

```json
{
  "name": "dma_fence_wait_any_timeout",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586665792,
      "name": "dma_fence_wait_any_timeout",
      "external": true,
      "loc": "drivers/dma-buf/dma-fence.c:562",
      "file": "drivers/dma-buf/dma-fence.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586665792,
      "name": "dma_fence_wait_any_timeout",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 585
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
long int dma_fence_wait_any_timeout(struct dma_fence * * fences, uint32_t count, bool intr, long int timeout, uint32_t * idx)
```
</details>
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
