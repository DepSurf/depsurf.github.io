# Function: <code>iommu_dma_map_page</code>

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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586785760,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:725",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586785760,
      "name": "iommu_dma_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586965440,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:828",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586965440,
      "name": "iommu_dma_map_page",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586848752,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:847",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586848752,
      "name": "iommu_dma_map_page",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587410144,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:860",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587410144,
      "name": "iommu_dma_map_page",
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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:966",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588722112,
      "name": "iommu_dma_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071594353424,
      "name": "iommu_dma_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:974",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590206320,
      "name": "iommu_dma_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071596244962,
      "name": "iommu_dma_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1015",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590527728,
      "name": "iommu_dma_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071596773362,
      "name": "iommu_dma_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:1134",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590883056,
      "name": "iommu_dma_map_page",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 694
    },
    {
      "addr": 18446744071597682611,
      "name": "iommu_dma_map_page.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 47
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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```

```json
{
  "name": "iommu_dma_map_page",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498846048,
      "name": "iommu_dma_map_page",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:704",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498846048,
      "name": "iommu_dma_map_page",
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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
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
dma_addr_t iommu_dma_map_page(struct device * dev, struct page * page, long unsigned int offset, size_t size, enum dma_data_direction dir, long unsigned int attrs)
```
</details>
</li>
</ul>
