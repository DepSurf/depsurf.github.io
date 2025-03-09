# Function: <code>qi_flush_piotlb</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "qi_flush_piotlb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_piotlb",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1400",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:domain_flush_piotlb",
        "drivers/iommu/intel/iommu.c:domain_flush_piotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836139,
      "name": "qi_flush_piotlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586833248,
      "name": "qi_flush_piotlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "qi_flush_piotlb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_piotlb",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1439",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:domain_flush_piotlb",
        "drivers/iommu/intel/iommu.c:domain_flush_piotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591478003,
      "name": "qi_flush_piotlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586889920,
      "name": "qi_flush_piotlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "qi_flush_piotlb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_piotlb",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1508",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:domain_flush_piotlb",
        "drivers/iommu/intel/iommu.c:domain_flush_piotlb",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591418717,
      "name": "qi_flush_piotlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    },
    {
      "addr": 18446744071586770832,
      "name": "qi_flush_piotlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "qi_flush_piotlb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_piotlb",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1537",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:domain_flush_piotlb",
        "drivers/iommu/intel/iommu.c:domain_flush_piotlb",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592472856,
      "name": "qi_flush_piotlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071587326016,
      "name": "qi_flush_piotlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 291
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
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "qi_flush_piotlb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_piotlb",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1533",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594342628,
      "name": "qi_flush_piotlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
    },
    {
      "addr": 18446744071588640752,
      "name": "qi_flush_piotlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 310
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
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "qi_flush_piotlb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_piotlb",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1522",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596241796,
      "name": "qi_flush_piotlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071590111040,
      "name": "qi_flush_piotlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "qi_flush_piotlb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_piotlb",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1543",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596770282,
      "name": "qi_flush_piotlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    },
    {
      "addr": 18446744071590424784,
      "name": "qi_flush_piotlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 329
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
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "qi_flush_piotlb",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_piotlb",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1552",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_flush_pasid_iotlb",
        "drivers/iommu/intel/iommu.c:domain_flush_pasid_iotlb",
        "drivers/iommu/intel/pasid.c:intel_pasid_setup_page_snoop_control",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/nested.c:intel_nested_cache_invalidate_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597678846,
      "name": "qi_flush_piotlb.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
    },
    {
      "addr": 18446744071590768944,
      "name": "qi_flush_piotlb",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 331
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
void qi_flush_piotlb(struct intel_iommu * iommu, u16 did, u32 pasid, u64 addr, long unsigned int npages, bool ih)
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
