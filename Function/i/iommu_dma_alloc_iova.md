# Function: <code>iommu_dma_alloc_iova</code>

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
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586782128,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:400",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586782128,
      "name": "iommu_dma_alloc_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586962736,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:431",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_get_msi_page",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586962736,
      "name": "iommu_dma_alloc_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586844432,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:417",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586844432,
      "name": "iommu_dma_alloc_iova",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:433",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587405680,
      "name": "iommu_dma_alloc_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 368
    },
    {
      "addr": 18446744071592483683,
      "name": "iommu_dma_alloc_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:614",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588717760,
      "name": "iommu_dma_alloc_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071594352698,
      "name": "iommu_dma_alloc_iova.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:625",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590200592,
      "name": "iommu_dma_alloc_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071596244277,
      "name": "iommu_dma_alloc_iova.cold",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:658",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590522080,
      "name": "iommu_dma_alloc_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 374
    },
    {
      "addr": 18446744071596772677,
      "name": "iommu_dma_alloc_iova.cold",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:763",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590878464,
      "name": "iommu_dma_alloc_iova",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 390
    },
    {
      "addr": 18446744071597681809,
      "name": "iommu_dma_alloc_iova.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 201
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_dma_alloc_iova",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336498845336,
      "name": "iommu_dma_alloc_iova",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:384",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi",
        "drivers/iommu/dma-iommu.c:iommu_dma_map_sg",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_remap",
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498845336,
      "name": "iommu_dma_alloc_iova.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 312
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
dma_addr_t iommu_dma_alloc_iova(struct iommu_domain * domain, size_t size, u64 dma_limit, struct device * dev)
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
