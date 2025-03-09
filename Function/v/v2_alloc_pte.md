# Function: <code>v2_alloc_pte</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
u64 * v2_alloc_pte(u64 * pgd, long unsigned int iova, long unsigned int pg_size, bool * updated)
```

```json
{
  "name": "v2_alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590097376,
      "name": "v2_alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable_v2.c:141",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590097376,
      "name": "v2_alloc_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 444
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
u64 * v2_alloc_pte(int nid, u64 * pgd, long unsigned int iova, long unsigned int pg_size, gfp_t gfp, bool * updated)
```

```json
{
  "name": "v2_alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "v2_alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable_v2.c:135",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590411264,
      "name": "v2_alloc_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
    },
    {
      "addr": 18446744071596769979,
      "name": "v2_alloc_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
u64 * v2_alloc_pte(int nid, u64 * pgd, long unsigned int iova, long unsigned int pg_size, gfp_t gfp, bool * updated)
```

```json
{
  "name": "v2_alloc_pte",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "v2_alloc_pte",
      "external": false,
      "loc": "drivers/iommu/amd/io_pgtable_v2.c:135",
      "file": "drivers/iommu/amd/io_pgtable_v2.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable_v2.c:iommu_v2_map_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590755376,
      "name": "v2_alloc_pte",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 722
    },
    {
      "addr": 18446744071597678536,
      "name": "v2_alloc_pte.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
u64 * v2_alloc_pte(u64 * pgd, long unsigned int iova, long unsigned int pg_size, bool * updated)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int nid</code>
</li>
<li>
<b>Param added. </b>
<code>gfp_t gfp</code>
</li>
<li>
<b>Param reordered. </b>
<code>pgd, iova, pg_size, updated</code> ➡️ <code>nid, pgd, iova, pg_size, gfp, updated</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
