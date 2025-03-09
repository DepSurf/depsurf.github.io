# Function: <code>intel_pasid_setup_second_level</code>

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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:545",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585745819,
      "name": "intel_pasid_setup_second_level.cold.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071585744672,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 636
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:530",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585977595,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585976384,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:538",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586122972,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586121888,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:608",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875021,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586873184,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:616",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591480678,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586922000,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 432
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:657",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591421126,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586803360,
      "name": "intel_pasid_setup_second_level",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:665",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592477538,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071587360352,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 528
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:602",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:domain_add_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594346824,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
    },
    {
      "addr": 18446744071588671920,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 512
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590145312,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:611",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590145312,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 578
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590459568,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:581",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590459568,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 557
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590806752,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:367",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590806752,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 576
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:538",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585883340,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585882256,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:538",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743116,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071585742032,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:538",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586072988,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586071904,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_second_level",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_second_level",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:538",
      "file": "drivers/iommu/intel-pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586181212,
      "name": "intel_pasid_setup_second_level.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
    },
    {
      "addr": 18446744071586180128,
      "name": "intel_pasid_setup_second_level",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 600
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
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
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_pasid_setup_second_level(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
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
