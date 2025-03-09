# Function: <code>xa_store_range</code>

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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589433552,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1569",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages",
        "kernel/memremap.c:devm_memremap_pages_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589433552,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 690
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589891552,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1547",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages",
        "mm/memremap.c:devm_memremap_pages_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589891552,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590117504,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1558",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590117504,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585119680,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1560",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585119680,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585270112,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1710",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pageunmap_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585270112,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585153344,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1711",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585153344,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 697
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1711",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592345755,
      "name": "xa_store_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 66
    },
    {
      "addr": 18446744071585606064,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 755
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594207226,
      "name": "xa_store_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071586763392,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 746
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1718",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596376192,
      "name": "xa_store_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071595927760,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 743
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1716",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596905569,
      "name": "xa_store_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071596446160,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1716",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/cpu/sgx/main.c:sgx_page_cache_init",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:pagemap_range",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597830662,
      "name": "xa_store_range.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446744071597341520,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 747
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503897408,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1558",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503897408,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 832
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297769232,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1558",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297769232,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1080
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589719760,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1558",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589719760,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589445536,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1558",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589445536,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590163136,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1558",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590163136,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 701
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```

```json
{
  "name": "xa_store_range",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590213920,
      "name": "xa_store_range",
      "external": true,
      "loc": "lib/xarray.c:1558",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memremap_pages",
        "mm/memremap.c:memunmap_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590213920,
      "name": "xa_store_range",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 699
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
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * xa_store_range(struct xarray * xa, long unsigned int first, long unsigned int last, void * entry, gfp_t gfp)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
