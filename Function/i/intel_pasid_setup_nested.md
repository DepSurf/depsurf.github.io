# Function: <code>intel_pasid_setup_nested</code>

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
int intel_pasid_setup_nested(struct intel_iommu * iommu, struct device * dev, pgd_t * gpgd, int pasid, struct iommu_gpasid_bind_data_vtd * pasid_data, struct dmar_domain * domain, int addr_width)
```

```json
{
  "name": "intel_pasid_setup_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_nested",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:753",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875128,
      "name": "intel_pasid_setup_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071586873872,
      "name": "intel_pasid_setup_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
int intel_pasid_setup_nested(struct intel_iommu * iommu, struct device * dev, pgd_t * gpgd, u32 pasid, struct iommu_gpasid_bind_data_vtd * pasid_data, struct dmar_domain * domain, int addr_width)
```

```json
{
  "name": "intel_pasid_setup_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_nested",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:761",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591480785,
      "name": "intel_pasid_setup_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071586922688,
      "name": "intel_pasid_setup_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 931
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
int intel_pasid_setup_nested(struct intel_iommu * iommu, struct device * dev, pgd_t * gpgd, u32 pasid, struct iommu_gpasid_bind_data_vtd * pasid_data, struct dmar_domain * domain, int addr_width)
```

```json
{
  "name": "intel_pasid_setup_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_nested",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:809",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591421233,
      "name": "intel_pasid_setup_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071586804096,
      "name": "intel_pasid_setup_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 937
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
int intel_pasid_setup_nested(struct intel_iommu * iommu, struct device * dev, pgd_t * gpgd, u32 pasid, struct iommu_gpasid_bind_data_vtd * pasid_data, struct dmar_domain * domain, int addr_width)
```

```json
{
  "name": "intel_pasid_setup_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_nested",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:825",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/svm.c:intel_svm_bind_gpasid"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592477645,
      "name": "intel_pasid_setup_nested.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
    },
    {
      "addr": 18446744071587361152,
      "name": "intel_pasid_setup_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1036
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
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int intel_pasid_setup_nested(struct intel_iommu * iommu, struct device * dev, u32 pasid, struct dmar_domain * domain)
```

```json
{
  "name": "intel_pasid_setup_nested",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590808656,
      "name": "intel_pasid_setup_nested",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:586",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/nested.c:intel_nested_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590808656,
      "name": "intel_pasid_setup_nested",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 909
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
int intel_pasid_setup_nested(struct intel_iommu * iommu, struct device * dev, pgd_t * gpgd, int pasid, struct iommu_gpasid_bind_data_vtd * pasid_data, struct dmar_domain * domain, int addr_width)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int intel_pasid_setup_nested(struct intel_iommu * iommu, struct device * dev, pgd_t * gpgd, u32 pasid, struct iommu_gpasid_bind_data_vtd * pasid_data, struct dmar_domain * domain, int addr_width)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➕</summary>

```c
int intel_pasid_setup_nested(struct intel_iommu * iommu, struct device * dev, u32 pasid, struct dmar_domain * domain)
```
</details>
</li>
</ul>
