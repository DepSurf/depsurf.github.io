# Function: <code>amd_iommu_domain_set_pgtable</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "amd_iommu_domain_set_pgtable",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586860522,
      "name": "amd_iommu_domain_set_pgtable",
      "external": false,
      "loc": "drivers/iommu/amd/iommu.c:173",
      "file": "drivers/iommu/amd/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc",
        "drivers/iommu/amd/iommu.c:increase_address_space"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void amd_iommu_domain_set_pgtable(struct protection_domain * domain, u64 * root, int mode)
```

```json
{
  "name": "amd_iommu_domain_set_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586758373,
      "name": "amd_iommu_domain_set_pgtable",
      "external": true,
      "loc": "drivers/iommu/amd/io_pgtable.c:160",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586761456,
      "name": "amd_iommu_domain_set_pgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void amd_iommu_domain_set_pgtable(struct protection_domain * domain, u64 * root, int mode)
```

```json
{
  "name": "amd_iommu_domain_set_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587313605,
      "name": "amd_iommu_domain_set_pgtable",
      "external": true,
      "loc": "drivers/iommu/amd/io_pgtable.c:160",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587316160,
      "name": "amd_iommu_domain_set_pgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 49
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
void amd_iommu_domain_set_pgtable(struct protection_domain * domain, u64 * root, int mode)
```

```json
{
  "name": "amd_iommu_domain_set_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588628398,
      "name": "amd_iommu_domain_set_pgtable",
      "external": true,
      "loc": "drivers/iommu/amd/io_pgtable.c:134",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588630512,
      "name": "amd_iommu_domain_set_pgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void amd_iommu_domain_set_pgtable(struct protection_domain * domain, u64 * root, int mode)
```

```json
{
  "name": "amd_iommu_domain_set_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590094334,
      "name": "amd_iommu_domain_set_pgtable",
      "external": true,
      "loc": "drivers/iommu/amd/io_pgtable.c:134",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590096688,
      "name": "amd_iommu_domain_set_pgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void amd_iommu_domain_set_pgtable(struct protection_domain * domain, u64 * root, int mode)
```

```json
{
  "name": "amd_iommu_domain_set_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590407153,
      "name": "amd_iommu_domain_set_pgtable",
      "external": true,
      "loc": "drivers/iommu/amd/io_pgtable.c:134",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590409792,
      "name": "amd_iommu_domain_set_pgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void amd_iommu_domain_set_pgtable(struct protection_domain * domain, u64 * root, int mode)
```

```json
{
  "name": "amd_iommu_domain_set_pgtable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590751185,
      "name": "amd_iommu_domain_set_pgtable",
      "external": true,
      "loc": "drivers/iommu/amd/io_pgtable.c:134",
      "file": "drivers/iommu/amd/io_pgtable.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:protection_domain_alloc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590753872,
      "name": "amd_iommu_domain_set_pgtable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void amd_iommu_domain_set_pgtable(struct protection_domain * domain, u64 * root, int mode)
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
