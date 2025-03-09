# Function: <code>amd_iommu_domain_update</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void amd_iommu_domain_update(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586752464,
      "name": "amd_iommu_domain_update",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1765",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586752464,
      "name": "amd_iommu_domain_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void amd_iommu_domain_update(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587306160,
      "name": "amd_iommu_domain_update",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1809",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/io_pgtable.c:v1_free_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587306160,
      "name": "amd_iommu_domain_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
void amd_iommu_domain_update(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588620368,
      "name": "amd_iommu_domain_update",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1831",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/io_pgtable.c:v1_free_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588620368,
      "name": "amd_iommu_domain_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void amd_iommu_domain_update(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590083216,
      "name": "amd_iommu_domain_update",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1955",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/io_pgtable.c:v1_free_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_free_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590083216,
      "name": "amd_iommu_domain_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
void amd_iommu_domain_update(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_update",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590395104,
      "name": "amd_iommu_domain_update",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:1980",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_enable_v2",
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/io_pgtable.c:v1_free_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_free_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590395104,
      "name": "amd_iommu_domain_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void amd_iommu_domain_update(struct protection_domain * domain)
```

```json
{
  "name": "amd_iommu_domain_update",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590737317,
      "name": "amd_iommu_domain_update",
      "external": true,
      "loc": "drivers/iommu/amd/iommu.c:2028",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc"
      ],
      "caller_func": [
        "drivers/iommu/amd/io_pgtable.c:v1_free_pgtable",
        "drivers/iommu/amd/io_pgtable_v2.c:v2_free_pgtable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590738288,
      "name": "amd_iommu_domain_update",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void amd_iommu_domain_update(struct protection_domain * domain)
```
</details>
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
