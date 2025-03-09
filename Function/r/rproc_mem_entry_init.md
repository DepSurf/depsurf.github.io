# Function: <code>rproc_mem_entry_init</code>

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
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588231344,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:960",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588231344,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, size_t len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589110032,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:971",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589110032,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, size_t len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589107152,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1005",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589107152,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 241
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, size_t len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588996576,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1011",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588996576,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, size_t len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589710768,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1025",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589710768,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 243
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, size_t len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591218176,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:1021",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591218176,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, size_t len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592964992,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:914",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592964992,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, size_t len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593415360,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:915",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593415360,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, size_t len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594161168,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:915",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594161168,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 335
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501687768,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:960",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501687768,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234213268,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:960",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234213268,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295123216,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:960",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295123216,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587843040,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:960",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587843040,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```

```json
{
  "name": "rproc_mem_entry_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588303680,
      "name": "rproc_mem_entry_init",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:960",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_handle_carveout",
        "drivers/remoteproc/remoteproc_core.c:rproc_alloc_vring"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588303680,
      "name": "rproc_mem_entry_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int len</code> ➡️ <code>size_t len</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
struct rproc_mem_entry * rproc_mem_entry_init(struct device * dev, void * va, dma_addr_t dma, int len, u32 da, int (*)(struct rproc *, struct rproc_mem_entry *) alloc, int (*)(struct rproc *, struct rproc_mem_entry *) release, const char * name, void (anon))
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
