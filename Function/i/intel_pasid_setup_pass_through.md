# Function: <code>intel_pasid_setup_pass_through</code>

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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585745312,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:618",
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
      "addr": 18446744071585745312,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 455
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:603",
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
      "addr": 18446744071585977674,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585976992,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:611",
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
      "addr": 18446744071586123051,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071586122496,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:666",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586875100,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071586873616,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:674",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591480757,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071586922432,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:719",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591421205,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071586803840,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:731",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592477617,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071587360880,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:665",
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
      "addr": 18446744071594346895,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071588672432,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 281
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590145920,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:678",
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
      "addr": 18446744071590145920,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 345
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590460144,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:642",
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
      "addr": 18446744071590460144,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct device * dev, u32 pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590807920,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:501",
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
      "addr": 18446744071590807920,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 324
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:611",
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
      "addr": 18446744071585883419,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585882864,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:611",
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
      "addr": 18446744071585743195,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071585742640,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:611",
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
      "addr": 18446744071586073067,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071586072512,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```

```json
{
  "name": "intel_pasid_setup_pass_through",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_setup_pass_through",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:611",
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
      "addr": 18446744071586181291,
      "name": "intel_pasid_setup_pass_through.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071586180736,
      "name": "intel_pasid_setup_pass_through",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct dmar_domain * domain</code>
</li>
<li>
<b>Param reordered. </b>
<code>iommu, domain, dev, pasid</code> ➡️ <code>iommu, dev, pasid</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_pasid_setup_pass_through(struct intel_iommu * iommu, struct dmar_domain * domain, struct device * dev, int pasid)
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
