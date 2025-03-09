# Function: <code>iommu_dma_init_fq</code>

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
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int iommu_dma_init_fq(struct iommu_domain * domain)
```

```json
{
  "name": "iommu_dma_init_fq",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587411751,
      "name": "iommu_dma_init_fq",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:321",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592484725,
      "name": "iommu_dma_init_fq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071587411936,
      "name": "iommu_dma_init_fq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 95
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
int iommu_dma_init_fq(struct iommu_domain * domain)
```

```json
{
  "name": "iommu_dma_init_fq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_dma_init_fq",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:238",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594353529,
      "name": "iommu_dma_init_fq.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071588726080,
      "name": "iommu_dma_init_fq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 378
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
int iommu_dma_init_fq(struct iommu_domain * domain)
```

```json
{
  "name": "iommu_dma_init_fq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590210464,
      "name": "iommu_dma_init_fq",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:241",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_change_dev_def_domain",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590210464,
      "name": "iommu_dma_init_fq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int iommu_dma_init_fq(struct iommu_domain * domain)
```

```json
{
  "name": "iommu_dma_init_fq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590531952,
      "name": "iommu_dma_init_fq",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:242",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_group_store_type",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590531952,
      "name": "iommu_dma_init_fq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int iommu_dma_init_fq(struct iommu_domain * domain)
```

```json
{
  "name": "iommu_dma_init_fq",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590887424,
      "name": "iommu_dma_init_fq",
      "external": true,
      "loc": "drivers/iommu/dma-iommu.c:334",
      "file": "drivers/iommu/dma-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/iommu.c:iommu_group_store_type",
        "drivers/iommu/dma-iommu.c:iommu_dma_init_domain"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590887424,
      "name": "iommu_dma_init_fq",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 489
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int iommu_dma_init_fq(struct iommu_domain * domain)
```
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
