# Function: <code>iommu_map_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584283865,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1257",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584626128,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1363",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626128,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 944
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
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584811232,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1453",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584811232,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 935
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
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584901136,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1512",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584901136,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 926
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
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585322416,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1453",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585322416,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 973
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
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585562736,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1459",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585562736,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 949
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1595",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585686448,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1093
    },
    {
      "addr": 18446744071585700897,
      "name": "iommu_map_page.cold.45",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
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
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1610",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585913968,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1125
    },
    {
      "addr": 18446744071585927719,
      "name": "iommu_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1658",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586057824,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1355
    },
    {
      "addr": 18446744071586071137,
      "name": "iommu_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1631",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586814256,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071586818151,
      "name": "iommu_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1722",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586873440,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 624
    },
    {
      "addr": 18446744071591474993,
      "name": "iommu_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
dma_addr_t iommu_map_page(struct device * dev, struct iommu_table * tbl, struct page * page, long unsigned int offset, size_t size, long unsigned int mask, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282502672,
      "name": "iommu_map_page",
      "external": true,
      "loc": "arch/powerpc/kernel/iommu.c:794",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_map_page",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282502672,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 516
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1658",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585818800,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1355
    },
    {
      "addr": 18446744071585832257,
      "name": "iommu_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1658",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677984,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1355
    },
    {
      "addr": 18446744071585691297,
      "name": "iommu_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1658",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586007840,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1355
    },
    {
      "addr": 18446744071586021153,
      "name": "iommu_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```

```json
{
  "name": "iommu_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_map_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1658",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586116128,
      "name": "iommu_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1355
    },
    {
      "addr": 18446744071586129105,
      "name": "iommu_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```
</details>
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
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
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param added. </b>
<code>struct iommu_table * tbl</code>
</li>
<li>
<b>Param added. </b>
<code>struct page * page</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int offset</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int mask</code>
</li>
<li>
<b>Param added. </b>
<code>enum dma_data_direction direction</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int attrs</code>
</li>
<li>
<b>Param removed. </b>
<code>struct protection_domain * dom</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int bus_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int phys_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int page_size</code>
</li>
<li>
<b>Param removed. </b>
<code>int prot</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>dma_addr_t</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int iommu_map_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int phys_addr, long unsigned int page_size, int prot, gfp_t gfp)
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
