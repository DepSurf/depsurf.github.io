# Function: <code>iommu_v1_map_pages</code>

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
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int iommu_v1_map_pages(struct io_pgtable_ops * ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t * mapped)
```

```json
{
  "name": "iommu_v1_map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_v1_map_pages",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:363",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590095696,
      "name": "iommu_v1_map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 966
    },
    {
      "addr": 18446744071596241569,
      "name": "iommu_v1_map_pages.cold",
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
int iommu_v1_map_pages(struct io_pgtable_ops * ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t * mapped)
```

```json
{
  "name": "iommu_v1_map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_v1_map_pages",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:363",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590408736,
      "name": "iommu_v1_map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1038
    },
    {
      "addr": 18446744071596769860,
      "name": "iommu_v1_map_pages.cold",
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
int iommu_v1_map_pages(struct io_pgtable_ops * ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t * mapped)
```

```json
{
  "name": "iommu_v1_map_pages",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "iommu_v1_map_pages",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable.c:363",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590752736,
      "name": "iommu_v1_map_pages",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1109
    },
    {
      "addr": 18446744071597678353,
      "name": "iommu_v1_map_pages.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int iommu_v1_map_pages(struct io_pgtable_ops * ops, long unsigned int iova, phys_addr_t paddr, size_t pgsize, size_t pgcount, int prot, gfp_t gfp, size_t * mapped)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
