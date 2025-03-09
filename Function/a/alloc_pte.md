# Function: <code>alloc_pte</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
u64 * alloc_pte(struct protection_domain * domain, long unsigned int address, long unsigned int page_size, u64 * * pte_page, gfp_t gfp)
```

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584280096,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1150",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:alloc_new_range",
        "drivers/iommu/amd_iommu.c:__map_single"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584280096,
      "name": "alloc_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 576
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584626192,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1246",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584811296,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1335",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584901200,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1394",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585322480,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1335",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585562851,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1341",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585686564,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1451",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585914104,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1466",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586057964,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1495",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586811840,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1452",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586811840,
      "name": "alloc_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586871360,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1543",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586871360,
      "name": "alloc_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586757856,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:221",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586757856,
      "name": "alloc_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 868
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
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:221",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587313280,
      "name": "alloc_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 922
    },
    {
      "addr": 18446744071592471167,
      "name": "alloc_pte.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
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
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:195",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588628128,
      "name": "alloc_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
    },
    {
      "addr": 18446744071594341010,
      "name": "alloc_pte.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:195",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590094064,
      "name": "alloc_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 917
    },
    {
      "addr": 18446744071596241412,
      "name": "alloc_pte.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 157
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
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:195",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590406816,
      "name": "alloc_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1224
    },
    {
      "addr": 18446744071596769695,
      "name": "alloc_pte.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:195",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:iommu_v1_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590750848,
      "name": "alloc_pte.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1214
    },
    {
      "addr": 18446744071597678188,
      "name": "alloc_pte.constprop.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270612560,
      "name": "alloc_pte",
      "external": false,
      "loc": "arch/riscv/mm/init.c:187",
      "file": "arch/riscv/mm/init.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/riscv/mm/init.c:create_pgd_mapping"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585818940,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1495",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585678124,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1495",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586007980,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1495",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586116268,
      "name": "alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1495",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:iommu_map_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
u64 * alloc_pte(struct protection_domain * domain, long unsigned int address, long unsigned int page_size, u64 * * pte_page, gfp_t gfp)
```
</details>
</li>
</ul>
