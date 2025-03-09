# Function: <code>iommu_dma_sync_single_for_cpu</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586781248,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:673",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781248,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 11
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586964800,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:756",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964800,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586846304,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:775",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846304,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587406176,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:795",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406176,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588718288,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:901",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588718288,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590201152,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:909",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590201152,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590522640,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:950",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590522640,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 141
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590879493,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1069",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590879888,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071597682101,
      "name": "iommu_dma_sync_single_for_cpu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_cpu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498845252,
      "name": "iommu_dma_sync_single_for_cpu",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:652",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_page"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498847216,
      "name": "iommu_dma_sync_single_for_cpu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
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
void iommu_dma_sync_single_for_cpu(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```
</details>
</li>
</ul>
