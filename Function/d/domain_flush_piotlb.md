# Function: <code>domain_flush_piotlb</code>

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
void domain_flush_piotlb(struct intel_iommu * iommu, struct dmar_domain * domain, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "domain_flush_piotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586836848,
      "name": "domain_flush_piotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1501",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:iommu_flush_iova",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586836848,
      "name": "domain_flush_piotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void domain_flush_piotlb(struct intel_iommu * iommu, struct dmar_domain * domain, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "domain_flush_piotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586892112,
      "name": "domain_flush_piotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1601",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586892112,
      "name": "domain_flush_piotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void domain_flush_piotlb(struct intel_iommu * iommu, struct dmar_domain * domain, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "domain_flush_piotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586773024,
      "name": "domain_flush_piotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1625",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773024,
      "name": "domain_flush_piotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
void domain_flush_piotlb(struct intel_iommu * iommu, struct dmar_domain * domain, u64 addr, long unsigned int npages, bool ih)
```

```json
{
  "name": "domain_flush_piotlb",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587328288,
      "name": "domain_flush_piotlb",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1629",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_flush_iotlb_all",
        "drivers/iommu/intel/iommu.c:iommu_flush_iotlb_psi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587328288,
      "name": "domain_flush_piotlb",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
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
void domain_flush_piotlb(struct intel_iommu * iommu, struct dmar_domain * domain, u64 addr, long unsigned int npages, bool ih)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void domain_flush_piotlb(struct intel_iommu * iommu, struct dmar_domain * domain, u64 addr, long unsigned int npages, bool ih)
```
</details>
</li>
</ul>
