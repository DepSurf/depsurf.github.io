# Function: <code>iommu_unmap_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584283230,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1301",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap"
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
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584623168,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1408",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584623168,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584804128,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1498",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584804128,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584893216,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1557",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584893216,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585314688,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1498",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585314688,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585555408,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1504",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585555408,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585680640,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1646",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585680640,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 245
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585907216,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1661",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585907216,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586050208,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1721",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586050208,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586799360,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1700",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586799360,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586858528,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:1791",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_unmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586858528,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 270
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
void iommu_unmap_page(struct iommu_table * tbl, dma_addr_t dma_handle, size_t size, enum dma_data_direction direction, long unsigned int attrs)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282503200,
      "name": "iommu_unmap_page",
      "external": true,
      "loc": "arch/powerpc/kernel/iommu.c:833",
      "file": "arch/powerpc/kernel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/dma-iommu.c:dma_iommu_unmap_page",
        "arch/powerpc/platforms/pseries/vio.c:vio_dma_iommu_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282503200,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585811184,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1721",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585811184,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585670368,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1721",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670368,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586000224,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1721",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586000224,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```

```json
{
  "name": "iommu_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586108416,
      "name": "iommu_unmap_page",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:1721",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_unmap",
        "drivers/iommu/amd_iommu.c:map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586108416,
      "name": "iommu_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 250
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
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
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
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
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
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iommu_table * tbl</code>
</li>
<li>
<b>Param added. </b>
<code>dma_addr_t dma_handle</code>
</li>
<li>
<b>Param added. </b>
<code>size_t size</code>
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
<code>long unsigned int page_size</code>
</li>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int iommu_unmap_page(struct protection_domain * dom, long unsigned int bus_addr, long unsigned int page_size)
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
