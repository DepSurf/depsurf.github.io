# Function: <code>iommu_dma_unmap_page</code>

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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586782016,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:741",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782016,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586964928,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:844",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586964928,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586846432,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:863",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586846432,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587408672,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:871",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408672,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588721120,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1020",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588721120,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590205168,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1028",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590205168,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590526624,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1070",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590526624,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1191",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_unmap_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590881888,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
    },
    {
      "addr": 18446744071597682590,
      "name": "iommu_dma_unmap_page.cold",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_unmap_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498845200,
      "name": "iommu_dma_unmap_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:720",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498845200,
      "name": "iommu_dma_unmap_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
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
void iommu_dma_unmap_page(struct device * dev, dma_addr_t dma_handle, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
</ul>
