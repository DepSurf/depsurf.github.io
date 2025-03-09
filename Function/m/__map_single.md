# Function: <code>__map_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
dma_addr_t __map_single(struct device * dev, struct dma_ops_domain * dma_dom, phys_addr_t paddr, size_t size, int dir, bool align, u64 dma_mask)
```

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584287616,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2371",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:map_sg",
        "drivers/iommu/amd_iommu.c:map_page",
        "drivers/iommu/amd_iommu.c:alloc_coherent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287616,
      "name": "__map_single",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1075
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
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584627072,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2283",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584627072,
      "name": "__map_single.isra.26",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584812176,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2376",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812176,
      "name": "__map_single.isra.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 421
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584903392,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2537",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584903392,
      "name": "__map_single.isra.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585324400,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2319",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585324400,
      "name": "__map_single.isra.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 443
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585563696,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2329",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563696,
      "name": "__map_single.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585689024,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2405",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585689024,
      "name": "__map_single.isra.31",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 433
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585916624,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2386",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585916624,
      "name": "__map_single.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 439
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586060944,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2409",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586060944,
      "name": "__map_single.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585821920,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2409",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585821920,
      "name": "__map_single.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585681104,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2409",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585681104,
      "name": "__map_single.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586010960,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2409",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586010960,
      "name": "__map_single.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "__map_single",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586119808,
      "name": "__map_single",
      "external": false,
      "loc": "drivers/iommu/amd_iommu.c:2409",
      "file": "drivers/iommu/amd_iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:alloc_coherent",
        "drivers/iommu/amd_iommu.c:map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586119808,
      "name": "__map_single.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 456
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
<summary>Removed between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➖</summary>

```c
dma_addr_t __map_single(struct device * dev, struct dma_ops_domain * dma_dom, phys_addr_t paddr, size_t size, int dir, bool align, u64 dma_mask)
```
</details>
</li>
</ul>
