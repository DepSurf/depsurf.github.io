# Function: <code>qi_flush_pasid_cache</code>

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
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, int pasid)
```

```json
{
  "name": "qi_flush_pasid_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586833824,
      "name": "qi_flush_pasid_cache",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1486",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586833824,
      "name": "qi_flush_pasid_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, u32 pasid)
```

```json
{
  "name": "qi_flush_pasid_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586890480,
      "name": "qi_flush_pasid_cache",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1523",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586890480,
      "name": "qi_flush_pasid_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, u32 pasid)
```

```json
{
  "name": "qi_flush_pasid_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586771392,
      "name": "qi_flush_pasid_cache",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1592",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:iommu_set_root_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771392,
      "name": "qi_flush_pasid_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, u32 pasid)
```

```json
{
  "name": "qi_flush_pasid_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587326688,
      "name": "qi_flush_pasid_cache",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1621",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:iommu_set_root_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587326688,
      "name": "qi_flush_pasid_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, u32 pasid)
```

```json
{
  "name": "qi_flush_pasid_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588641456,
      "name": "qi_flush_pasid_cache",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1617",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:iommu_set_root_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588641456,
      "name": "qi_flush_pasid_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, u32 pasid)
```

```json
{
  "name": "qi_flush_pasid_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590111824,
      "name": "qi_flush_pasid_cache",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1606",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:iommu_set_root_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590111824,
      "name": "qi_flush_pasid_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, u32 pasid)
```

```json
{
  "name": "qi_flush_pasid_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590425568,
      "name": "qi_flush_pasid_cache",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1627",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:iommu_set_root_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590425568,
      "name": "qi_flush_pasid_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, u32 pasid)
```

```json
{
  "name": "qi_flush_pasid_cache",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590769744,
      "name": "qi_flush_pasid_cache",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1645",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_context_clear_one",
        "drivers/iommu/intel/iommu.c:iommu_set_root_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590769744,
      "name": "qi_flush_pasid_cache",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void qi_flush_pasid_cache(struct intel_iommu * iommu, u16 did, u64 granu, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int pasid</code> ➡️ <code>u32 pasid</code>
</li>
</ul>
</details>
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
