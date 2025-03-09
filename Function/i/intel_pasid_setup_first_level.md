# Function: <code>intel_pasid_setup_first_level</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:487",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585745767,
      "name": "intel_pasid_setup_first_level.cold.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585744128,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 542
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:472",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977519,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446744071585975840,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 531
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:472",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586122920,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586121328,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:535",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586874875,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071586872752,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, u32 pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:543",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591480532,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 146
    },
    {
      "addr": 18446744071586921568,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 422
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, u32 pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:578",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591420959,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071586802832,
      "name": "intel_pasid_setup_first_level",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, u32 pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:582",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_setup_first_level",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592477371,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
    },
    {
      "addr": 18446744071587359792,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 547
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, u32 pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:519",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_add_dev_info",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594346714,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 110
    },
    {
      "addr": 18446744071588671328,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 579
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, u32 pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590144624,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:512",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590144624,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 667
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, u32 pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590458992,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:503",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590458992,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, u32 pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590806176,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:289",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_setup_first_level"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590806176,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 552
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:472",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585883288,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585881696,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:472",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743064,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071585741472,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:472",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072936,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586071344,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```

```json
{
  "name": "intel_pasid_setup_first_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_first_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:472",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm",
        "drivers/iommu/intel-svm.c:intel_svm_bind_mm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586181160,
      "name": "intel_pasid_setup_first_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 52
    },
    {
      "addr": 18446744071586179568,
      "name": "intel_pasid_setup_first_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 549
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_pasid_setup_first_level(struct intel_iommu * iommu, struct device * dev, pgd_t * pgd, int pasid, u16 did, int flags)
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
