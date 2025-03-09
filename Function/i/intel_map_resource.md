# Function: <code>intel_map_resource</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "intel_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585968864,
      "name": "intel_map_resource",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3558",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585968864,
      "name": "intel_map_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "intel_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586114784,
      "name": "intel_map_resource",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3573",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586114784,
      "name": "intel_map_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "intel_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586865472,
      "name": "intel_map_resource",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:3457",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586865472,
      "name": "intel_map_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "intel_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585875152,
      "name": "intel_map_resource",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3573",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585875152,
      "name": "intel_map_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "intel_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585734928,
      "name": "intel_map_resource",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3573",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585734928,
      "name": "intel_map_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "intel_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586064800,
      "name": "intel_map_resource",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3573",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586064800,
      "name": "intel_map_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "intel_map_resource",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586172928,
      "name": "intel_map_resource",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:3573",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586172928,
      "name": "intel_map_resource",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
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
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
dma_addr_t intel_map_resource(struct device * dev, phys_addr_t phys_addr, size_t size, enum dma_data_direction dir, long unsigned int attrs)
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
