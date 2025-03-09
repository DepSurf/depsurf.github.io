# Function: <code>qi_flush_dev_iotlb_pasid</code>

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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order, u64 granu)
```

```json
{
  "name": "qi_flush_dev_iotlb_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_dev_iotlb_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1441",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836160,
      "name": "qi_flush_dev_iotlb_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586833504,
      "name": "qi_flush_dev_iotlb_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order)
```

```json
{
  "name": "qi_flush_dev_iotlb_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_dev_iotlb_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1480",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591478024,
      "name": "qi_flush_dev_iotlb_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586890160,
      "name": "qi_flush_dev_iotlb_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order)
```

```json
{
  "name": "qi_flush_dev_iotlb_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_dev_iotlb_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1549",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591418738,
      "name": "qi_flush_dev_iotlb_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071586771088,
      "name": "qi_flush_dev_iotlb_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 303
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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order)
```

```json
{
  "name": "qi_flush_dev_iotlb_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_dev_iotlb_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1578",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_sva_invalidate",
        "drivers/iommu/intel/pasid.c:intel_pasid_tear_down_entry",
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592472954,
      "name": "qi_flush_dev_iotlb_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071587326320,
      "name": "qi_flush_dev_iotlb_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 353
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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order)
```

```json
{
  "name": "qi_flush_dev_iotlb_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_dev_iotlb_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1574",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_invalidate_range"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594342726,
      "name": "qi_flush_dev_iotlb_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 219
    },
    {
      "addr": 18446744071588641072,
      "name": "qi_flush_dev_iotlb_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 380
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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order)
```

```json
{
  "name": "qi_flush_dev_iotlb_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_dev_iotlb_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1563",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596241889,
      "name": "qi_flush_dev_iotlb_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
    },
    {
      "addr": 18446744071590111392,
      "name": "qi_flush_dev_iotlb_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 402
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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order)
```

```json
{
  "name": "qi_flush_dev_iotlb_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_dev_iotlb_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1584",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596770375,
      "name": "qi_flush_dev_iotlb_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071590425136,
      "name": "qi_flush_dev_iotlb_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 406
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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order)
```

```json
{
  "name": "qi_flush_dev_iotlb_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "qi_flush_dev_iotlb_pasid",
      "external": true,
      "loc": "drivers/iommu/intel/dmar.c:1593",
      "file": "drivers/iommu/intel/dmar.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597678929,
      "name": "qi_flush_dev_iotlb_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071590769296,
      "name": "qi_flush_dev_iotlb_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 425
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
void qi_flush_dev_iotlb_pasid(struct intel_iommu * iommu, u16 sid, u16 pfsid, u32 pasid, u16 qdep, u64 addr, unsigned int size_order, u64 granu)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u64 granu</code>
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
