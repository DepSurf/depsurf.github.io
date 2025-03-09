# Function: <code>reserve_iova</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584272864,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:452",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584272864,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584613744,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:533",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613744,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584796944,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:533",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584796944,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584885904,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:507",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584885904,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 215
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585306448,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:651",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585306448,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585547344,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:651",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547344,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670624,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:660",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670624,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:659",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902830,
      "name": "reserve_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071585897984,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586040832,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:661",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586040832,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586790336,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:661",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/intel/iommu.c:intel_iommu_apply_resv_region",
        "drivers/iommu/intel/iommu.c:dmar_init_reserved_ranges",
        "drivers/iommu/intel/iommu.c:dmar_init_reserved_ranges"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586790336,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586971984,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:676",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/iova.c:copy_reserved_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586971984,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586853568,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:743",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586853568,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 271
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:755",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592485021,
      "name": "reserve_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071587416976,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 360
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:572",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594354086,
      "name": "reserve_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071588732464,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:577",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596245281,
      "name": "reserve_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590217584,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 391
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:577",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596773648,
      "name": "reserve_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590537360,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:578",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows",
        "drivers/iommu/dma-iommu.c:iova_reserve_pci_windows"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597682924,
      "name": "reserve_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071590892752,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 393
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498860760,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:661",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops",
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops",
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops",
        "drivers/iommu/iova.c:copy_reserved_iova"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498860760,
      "name": "reserve_iova",
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585801808,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:661",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585801808,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585660992,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:661",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660992,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585990848,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:661",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585990848,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```

```json
{
  "name": "reserve_iova",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586098768,
      "name": "reserve_iova",
      "external": true,
      "loc": "drivers/iommu/iova.c:661",
      "file": "drivers/iommu/iova.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iova.c:copy_reserved_iova",
        "drivers/iommu/amd_iommu.c:amd_iommu_apply_resv_region",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/amd_iommu.c:amd_iommu_init_api",
        "drivers/iommu/intel-iommu.c:intel_iommu_apply_resv_region",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:intel_iommu_init",
        "drivers/iommu/intel-iommu.c:iommu_domain_identity_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098768,
      "name": "reserve_iova",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 278
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
struct iova * reserve_iova(struct iova_domain * iovad, long unsigned int pfn_lo, long unsigned int pfn_hi)
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
