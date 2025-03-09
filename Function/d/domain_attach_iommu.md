# Function: <code>domain_attach_iommu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584324768,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1743",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584671568,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1783",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584858736,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1807",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584947805,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1812",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585369149,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1814",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585611548,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1842",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585735860,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1728",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1719",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585954912,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071585971777,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586098285,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1730",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586098192,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071586117417,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1807",
      "file": "drivers/iommu/intel/iommu.c",
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
      "addr": 18446744071586848352,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071586868653,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1906",
      "file": "drivers/iommu/intel/iommu.c",
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
      "addr": 18446744071586906144,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071591478841,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1912",
      "file": "drivers/iommu/intel/iommu.c",
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
      "addr": 18446744071586782752,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071591419197,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587339324,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1913",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:aux_domain_add_dev",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587339216,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
    },
    {
      "addr": 18446744071592474165,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588664223,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1811",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/iommu/intel/iommu.c:domain_add_dev_info"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590125120,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1776",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590125120,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 418
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
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590439632,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel/iommu.c:1744",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590439632,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 430
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
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590798416,
      "name": "domain_attach_iommu",
      "external": true,
      "loc": "drivers/iommu/intel/iommu.c:1695",
      "file": "drivers/iommu/intel/iommu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device",
        "drivers/iommu/intel/nested.c:intel_nested_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590798416,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 475
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585859405,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1730",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585859312,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071585877785,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585718429,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1730",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585718336,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071585737561,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586048301,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1730",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586048208,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071586067433,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```

```json
{
  "name": "domain_attach_iommu",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586156621,
      "name": "domain_attach_iommu",
      "external": false,
      "loc": "drivers/iommu/intel-iommu.c:1730",
      "file": "drivers/iommu/intel-iommu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586156528,
      "name": "domain_attach_iommu",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446744071586175609,
      "name": "domain_attach_iommu.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
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
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int domain_attach_iommu(struct dmar_domain * domain, struct intel_iommu * iommu)
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
