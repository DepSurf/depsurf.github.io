# Function: <code>__iommu_map</code>

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
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```

```json
{
  "name": "__iommu_map",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_map",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2171",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586776886,
      "name": "__iommu_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071586773216,
      "name": "__iommu_map",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```

```json
{
  "name": "__iommu_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_map",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2381",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952592,
      "name": "__iommu_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071591482882,
      "name": "__iommu_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```

```json
{
  "name": "__iommu_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_map",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2412",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586831504,
      "name": "__iommu_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 480
    },
    {
      "addr": 18446744071591426220,
      "name": "__iommu_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```

```json
{
  "name": "__iommu_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_map",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2482",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587392704,
      "name": "__iommu_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 613
    },
    {
      "addr": 18446744071592483232,
      "name": "__iommu_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
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
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```

```json
{
  "name": "__iommu_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_map",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2259",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588702272,
      "name": "__iommu_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 635
    },
    {
      "addr": 18446744071594352324,
      "name": "__iommu_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```

```json
{
  "name": "__iommu_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_map",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2323",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:__iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590182784,
      "name": "__iommu_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071596244144,
      "name": "__iommu_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```

```json
{
  "name": "__iommu_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_map",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2342",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_create_device_direct_mappings"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590508720,
      "name": "__iommu_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071596772553,
      "name": "__iommu_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```

```json
{
  "name": "__iommu_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__iommu_map",
      "external": false,
      "loc": "drivers/iommu/iommu.c:2607",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_map_sg",
        "drivers/iommu/iommu.c:iommu_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590861088,
      "name": "__iommu_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 634
    },
    {
      "addr": 18446744071597681618,
      "name": "__iommu_map.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int __iommu_map(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot, gfp_t gfp)
```
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
