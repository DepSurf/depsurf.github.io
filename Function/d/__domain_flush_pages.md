# Function: <code>__domain_flush_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584281792,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1039",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:__map_single",
        "drivers/iommu/amd_iommu.c:__map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584281792,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 504
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584624032,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1135",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:__queue_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584624032,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 542
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584809168,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1224",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:__queue_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584809168,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584896064,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1283",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:dma_ops_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584896064,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585317264,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1224",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585317264,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585560192,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1230",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585560192,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585685808,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1245",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585685808,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 255
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1244",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913312,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 262
    },
    {
      "addr": 18446744071585927700,
      "name": "__domain_flush_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586057168,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1266",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:update_domain",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586057168,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802144,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1210",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_map",
        "drivers/iommu/amd/iommu.c:update_domain",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:iommu_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802144,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586861312,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1300",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_map",
        "drivers/iommu/amd/iommu.c:update_domain",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:iommu_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586861312,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 269
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586739200,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1232",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_map",
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_update",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586739200,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 431
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1244",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587292896,
      "name": "__domain_flush_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    },
    {
      "addr": 18446744071592468616,
      "name": "__domain_flush_pages.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1266",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588608256,
      "name": "__domain_flush_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 494
    },
    {
      "addr": 18446744071594338838,
      "name": "__domain_flush_pages.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1348",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590070848,
      "name": "__domain_flush_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
    },
    {
      "addr": 18446744071596240428,
      "name": "__domain_flush_pages.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1368",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590383792,
      "name": "__domain_flush_pages.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 375
    },
    {
      "addr": 18446744071596768577,
      "name": "__domain_flush_pages.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590725536,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1461",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590725536,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 550
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585818144,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1266",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:update_domain",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818144,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585677328,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1266",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:update_domain",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677328,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586007184,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1266",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:update_domain",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007184,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```

```json
{
  "name": "__domain_flush_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586115472,
      "name": "__domain_flush_pages",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1266",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:update_domain",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586115472,
      "name": "__domain_flush_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 271
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __domain_flush_pages(struct protection_domain * domain, u64 address, size_t size, int pde)
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
