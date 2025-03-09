# Function: <code>__iommu_dma_map</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586782368,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:478",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782368,
      "name": "__iommu_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586962976,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:530",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586962976,
      "name": "__iommu_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 214
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586844688,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:513",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844688,
      "name": "__iommu_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 240
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587409072,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:530",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587409072,
      "name": "__iommu_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 237
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588721744,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:686",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588721744,
      "name": "__iommu_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590205920,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:697",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590205920,
      "name": "__iommu_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 225
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590527328,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:730",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590527328,
      "name": "__iommu_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590882656,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:849",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590882656,
      "name": "__iommu_dma_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot)
```

```json
{
  "name": "__iommu_dma_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498845648,
      "name": "__iommu_dma_map",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:463",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_resource",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498845648,
      "name": "__iommu_dma_map",
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
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot, u64 dma_mask)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
dma_addr_t __iommu_dma_map(struct device * dev, phys_addr_t phys, size_t size, int prot)
```
</details>
</li>
</ul>
