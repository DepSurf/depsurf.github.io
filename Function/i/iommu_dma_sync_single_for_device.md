# Function: <code>iommu_dma_sync_single_for_device</code>

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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:685",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586783392,
      "name": "iommu_dma_sync_single_for_device",
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586964672,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:772",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964672,
      "name": "iommu_dma_sync_single_for_device",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586846176,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:791",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846176,
      "name": "iommu_dma_sync_single_for_device",
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587406048,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:811",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587406048,
      "name": "iommu_dma_sync_single_for_device",
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588718144,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:917",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588718144,
      "name": "iommu_dma_sync_single_for_device",
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590200992,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:925",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590200992,
      "name": "iommu_dma_sync_single_for_device",
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590522480,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:966",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590522480,
      "name": "iommu_dma_sync_single_for_device",
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590879237,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1085",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590879664,
      "name": "iommu_dma_sync_single_for_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
    },
    {
      "addr": 18446744071597682080,
      "name": "iommu_dma_sync_single_for_device.cold",
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```

```json
{
  "name": "iommu_dma_sync_single_for_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498845096,
      "name": "iommu_dma_sync_single_for_device",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:664",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498845096,
      "name": "iommu_dma_sync_single_for_device",
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
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
void iommu_dma_sync_single_for_device(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir)
```
</details>
</li>
</ul>
