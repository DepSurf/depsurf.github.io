# Function: <code>__xa_cmpxchg</code>

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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589432400,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1416",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589432400,
      "name": "__xa_cmpxchg",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589890400,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1434",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589890400,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590116352,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590116352,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585120768,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1447",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585120768,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585271328,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1597",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585271328,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155072,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1598",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155072,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 309
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585607920,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1598",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "drivers/vfio/vfio.c:vfio_assign_device_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585607920,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 313
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586764528,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1605",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "drivers/vfio/vfio.c:vfio_assign_device_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586764528,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595928944,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1605",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595928944,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596447344,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1603",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596447344,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597342704,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1603",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_swapin_folio",
        "mm/shmem.c:shmem_undo_range",
        "mm/shmem.c:shmem_undo_range",
        "drivers/iommu/intel/iommu.c:domain_attach_iommu",
        "drivers/iommu/iommu.c:iommu_attach_device_pasid",
        "net/netlink/genetlink.c:genl_sk_priv_get"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597342704,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503899520,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503899520,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 328
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236527164,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236527164,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 388
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297767504,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297767504,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 440
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279787618,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279787618,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 224
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589718608,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589718608,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589444384,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589444384,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590161984,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590161984,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
```

```json
{
  "name": "__xa_cmpxchg",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590212768,
      "name": "__xa_cmpxchg",
      "external": true,
      "loc": "lib/xarray.c:1445",
      "file": "lib/xarray.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/shmem.c:shmem_free_swap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590212768,
      "name": "__xa_cmpxchg",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void * __xa_cmpxchg(struct xarray * xa, long unsigned int index, void * old, void * entry, gfp_t gfp)
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
