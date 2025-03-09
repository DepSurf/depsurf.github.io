# Function: <code>intel_pasid_tear_down_entry</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585743712,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:459",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743712,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 412
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:444",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977481,
      "name": "intel_pasid_tear_down_entry.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
    },
    {
      "addr": 18446744071585975424,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 410
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586120912,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:444",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586120912,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid, bool fault_ignore)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586872272,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:492",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872272,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, u32 pasid, bool fault_ignore)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586921072,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:500",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_remove_dev",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586921072,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 495
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
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, u32 pasid, bool fault_ignore)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586802256,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:510",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586802256,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 573
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
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, u32 pasid, bool fault_ignore)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587359216,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:510",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_unbind_gpasid",
        "drivers/iommu/intel/svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587359216,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 575
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
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, u32 pasid, bool fault_ignore)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670800,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:447",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel/svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670800,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 521
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
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, u32 pasid, bool fault_ignore)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590144064,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:456",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590144064,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 538
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
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, u32 pasid, bool fault_ignore)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590458432,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:447",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590458432,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, u32 pasid, bool fault_ignore)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590805616,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:233",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_remove_dev_pasid",
        "drivers/iommu/intel/iommu.c:intel_iommu_release_device",
        "drivers/iommu/intel/iommu.c:device_block_translation",
        "drivers/iommu/intel/svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590805616,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 541
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585881280,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:444",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585881280,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585741056,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:444",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585741056,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586070928,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:444",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586070928,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_tear_down_entry",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586179152,
      "name": "intel_pasid_tear_down_entry",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:444",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:intel_iommu_aux_detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info",
        "drivers/iommu/intel-svm.c:intel_svm_unbind_mm",
        "drivers/iommu/intel-svm.c:intel_mm_release"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586179152,
      "name": "intel_pasid_tear_down_entry",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 416
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```
</details>
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool fault_ignore</code>
</li>
</ul>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void intel_pasid_tear_down_entry(struct intel_iommu * iommu, struct device * dev, int pasid)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
