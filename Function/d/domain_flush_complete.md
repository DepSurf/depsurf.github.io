# Function: <code>domain_flush_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584275632,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1088",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:unmap_sg",
        "drivers/iommu/amd_iommu.c:unmap_page",
        "drivers/iommu/amd_iommu.c:free_coherent",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_page",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584275632,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 86
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584624673,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1184",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:__queue_flush"
      ],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584618496,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584804560,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1273",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__queue_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804560,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 114
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584893984,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1332",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:dma_ops_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893984,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585315456,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1273",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585315456,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585556192,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1279",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585556192,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585681328,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1294",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681328,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585907904,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1293",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:amd_iommu_map",
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585907904,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586051104,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1315",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586051104,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586799664,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1253",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_map",
        "drivers/iommu/amd/iommu.c:update_domain",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:iommu_map_page",
        "drivers/iommu/amd/iommu.c:increase_address_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799664,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586858832,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1343",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:__flush_pasid",
        "drivers/iommu/amd/iommu.c:amd_iommu_iotlb_sync",
        "drivers/iommu/amd/iommu.c:amd_iommu_map",
        "drivers/iommu/amd/iommu.c:update_domain",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/amd/iommu.c:do_detach",
        "drivers/iommu/amd/iommu.c:iommu_map_page",
        "drivers/iommu/amd/iommu.c:increase_address_space"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586858832,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585812080,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1315",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585812080,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585671264,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1315",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585671264,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586001120,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1315",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586001120,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void domain_flush_complete(struct protection_domain * domain)
```

```json
{
  "name": "domain_flush_complete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586109312,
      "name": "domain_flush_complete",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1315",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:__flush_pasid",
        "drivers/iommu/amd_iommu.c:amd_iommu_flush_iotlb_all",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/amd_iommu.c:do_detach",
        "drivers/iommu/amd_iommu.c:iova_domain_flush_tlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586109312,
      "name": "domain_flush_complete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void domain_flush_complete(struct protection_domain * domain)
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
void domain_flush_complete(struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void domain_flush_complete(struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void domain_flush_complete(struct protection_domain * domain)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void domain_flush_complete(struct protection_domain * domain)
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
