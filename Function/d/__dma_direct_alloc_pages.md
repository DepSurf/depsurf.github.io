# Function: <code>__dma_direct_alloc_pages</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579994656,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:96",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579994656,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580036720,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580036720,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580086960,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580086960,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580146960,
      "name": "__dma_direct_alloc_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:112",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580146960,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, gfp_t gfp)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580124352,
      "name": "__dma_direct_alloc_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:78",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580124352,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 649
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, gfp_t gfp)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580128736,
      "name": "__dma_direct_alloc_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:78",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580128736,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 618
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, gfp_t gfp)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580272176,
      "name": "__dma_direct_alloc_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:87",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272176,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 499
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580443568,
      "name": "__dma_direct_alloc_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:117",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580443568,
      "name": "__dma_direct_alloc_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 530
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580687792,
      "name": "__dma_direct_alloc_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:117",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580687792,
      "name": "__dma_direct_alloc_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 611
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580764400,
      "name": "__dma_direct_alloc_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:118",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580764400,
      "name": "__dma_direct_alloc_pages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 623
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580850144,
      "name": "__dma_direct_alloc_pages",
      "external": false,
      "loc": "kernel/dma/direct.c:118",
      "file": "kernel/dma/direct.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/direct.c:dma_direct_alloc",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580850144,
      "name": "__dma_direct_alloc_pages.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 626
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491289848,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages",
        "kernel/dma/remap.c:arch_dma_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491289848,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225295440,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225295440,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 588
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284215824,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284215824,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271805398,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271805398,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 372
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580055840,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580055840,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 439
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580001008,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001008,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047232,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047232,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "__dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580097984,
      "name": "__dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:85",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580097984,
      "name": "__dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 487
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>dma_addr_t * dma_handle</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, size, dma_handle, gfp, attrs</code> ➡️ <code>dev, size, gfp, attrs</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int attrs</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
struct page * __dma_direct_alloc_pages(struct device * dev, size_t size, gfp_t gfp)
```
</details>
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
