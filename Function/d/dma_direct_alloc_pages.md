# Function: <code>dma_direct_alloc_pages</code>

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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579995088,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:145",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579995088,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580037216,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580037216,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580087456,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580087456,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580147760,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:156",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580147760,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 411
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
struct page * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, enum dma_data_direction dir, gfp_t gfp)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580126688,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:279",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580126688,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
struct page * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, enum dma_data_direction dir, gfp_t gfp)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580131008,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:279",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580131008,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
struct page * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, enum dma_data_direction dir, gfp_t gfp)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:318",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592150010,
      "name": "dma_direct_alloc_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071580274464,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 434
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
struct page * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, enum dma_data_direction dir, gfp_t gfp)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580446048,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:367",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580446048,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct page * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, enum dma_data_direction dir, gfp_t gfp)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580690464,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:367",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580690464,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct page * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, enum dma_data_direction dir, gfp_t gfp)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580767072,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:366",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767072,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 437
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
struct page * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, enum dma_data_direction dir, gfp_t gfp)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580852816,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:355",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/mapping.c:__dma_alloc_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852816,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 443
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491290376,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491290376,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 260
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225296028,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225296028,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284216288,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284216288,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 408
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271805770,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271805770,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580056288,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580056288,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580001504,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580001504,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580047728,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580047728,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
```

```json
{
  "name": "dma_direct_alloc_pages",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580098480,
      "name": "dma_direct_alloc_pages",
      "external": true,
      "loc": "kernel/dma/direct.c:128",
      "file": "kernel/dma/direct.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_gart_64.c:gart_alloc_coherent",
        "kernel/dma/direct.c:dma_direct_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580098480,
      "name": "dma_direct_alloc_pages",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 299
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
void * dma_direct_alloc_pages(struct device * dev, size_t size, dma_addr_t * dma_handle, gfp_t gfp, long unsigned int attrs)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum dma_data_direction dir</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int attrs</code>
</li>
<li>
<b>Param reordered. </b>
<code>dev, size, dma_handle, gfp, attrs</code> ➡️ <code>dev, size, dma_handle, dir, gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>struct page *</code>
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
