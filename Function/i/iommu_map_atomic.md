# Function: <code>iommu_map_atomic</code>

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
int iommu_map_atomic(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot)
```

```json
{
  "name": "iommu_map_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586773856,
      "name": "iommu_map_atomic",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2239",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773856,
      "name": "iommu_map_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
int iommu_map_atomic(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot)
```

```json
{
  "name": "iommu_map_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586953456,
      "name": "iommu_map_atomic",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2459",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586953456,
      "name": "iommu_map_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
int iommu_map_atomic(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot)
```

```json
{
  "name": "iommu_map_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586832336,
      "name": "iommu_map_atomic",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2490",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586832336,
      "name": "iommu_map_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int iommu_map_atomic(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot)
```

```json
{
  "name": "iommu_map_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587393824,
      "name": "iommu_map_atomic",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2563",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587393824,
      "name": "iommu_map_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
int iommu_map_atomic(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot)
```

```json
{
  "name": "iommu_map_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588703504,
      "name": "iommu_map_atomic",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2340",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588703504,
      "name": "iommu_map_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
int iommu_map_atomic(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot)
```

```json
{
  "name": "iommu_map_atomic",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590184128,
      "name": "iommu_map_atomic",
      "external": true,
      "loc": "drivers/iommu/iommu.c:2404",
      "file": "drivers/iommu/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/dma-iommu.c:__iommu_dma_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590184128,
      "name": "iommu_map_atomic",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
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
int iommu_map_atomic(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot)
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int iommu_map_atomic(struct iommu_domain * domain, long unsigned int iova, phys_addr_t paddr, size_t size, int prot)
```
</details>
</li>
</ul>
