# Function: <code>iommu_dma_init_domain</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586785990,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:302",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_dma_init_domain(struct iommu_domain * domain, dma_addr_t base, u64 size, struct device * dev)
```

```json
{
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:329",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586966832,
      "name": "iommu_dma_init_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 408
    },
    {
      "addr": 18446744071591483110,
      "name": "iommu_dma_init_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_dma_init_domain(struct iommu_domain * domain, dma_addr_t base, u64 size, struct device * dev)
```

```json
{
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:332",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586847584,
      "name": "iommu_dma_init_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 361
    },
    {
      "addr": 18446744071591426639,
      "name": "iommu_dma_init_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int iommu_dma_init_domain(struct iommu_domain * domain, dma_addr_t base, dma_addr_t limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:356",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587411456,
      "name": "iommu_dma_init_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 379
    },
    {
      "addr": 18446744071592484447,
      "name": "iommu_dma_init_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
int iommu_dma_init_domain(struct iommu_domain * domain, dma_addr_t base, dma_addr_t limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:533",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588726464,
      "name": "iommu_dma_init_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071594353551,
      "name": "iommu_dma_init_domain.cold",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_dma_init_domain(struct iommu_domain * domain, dma_addr_t base, dma_addr_t limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:537",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590210880,
      "name": "iommu_dma_init_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 395
    },
    {
      "addr": 18446744071596245040,
      "name": "iommu_dma_init_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int iommu_dma_init_domain(struct iommu_domain * domain, dma_addr_t base, dma_addr_t limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:569",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590532368,
      "name": "iommu_dma_init_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 420
    },
    {
      "addr": 18446744071596773407,
      "name": "iommu_dma_init_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
int iommu_dma_init_domain(struct iommu_domain * domain, dma_addr_t base, dma_addr_t limit, struct device * dev)
```

```json
{
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:672",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590887936,
      "name": "iommu_dma_init_domain",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071597682683,
      "name": "iommu_dma_init_domain.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
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
  "name": "iommu_dma_init_domain",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336498849452,
      "name": "iommu_dma_init_domain",
      "external": false,
      "loc": "drivers/iommu/dma-iommu.c:301",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_setup_dma_ops"
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int iommu_dma_init_domain(struct iommu_domain * domain, dma_addr_t base, u64 size, struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>dma_addr_t limit</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 size</code>
</li>
</ul>
</details>
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
