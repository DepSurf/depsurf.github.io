# Function: <code>intel_pasid_alloc_table</code>

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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585742720,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:122",
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
      "addr": 18446744071585742720,
      "name": "intel_pasid_alloc_table",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:122",
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
      "addr": 18446744071585977435,
      "name": "intel_pasid_alloc_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071585974416,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 431
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586119888,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:122",
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
      "addr": 18446744071586119888,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586871216,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:143",
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
      "addr": 18446744071586871216,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 421
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586920016,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:143",
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
      "addr": 18446744071586920016,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 435
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586801536,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:142",
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
      "addr": 18446744071586801536,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 433
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:142",
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
      "addr": 18446744071592477336,
      "name": "intel_pasid_alloc_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
    },
    {
      "addr": 18446744071587358480,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 450
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:94",
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
      "addr": 18446744071594346683,
      "name": "intel_pasid_alloc_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071588670192,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 349
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:94",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596243651,
      "name": "intel_pasid_alloc_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    },
    {
      "addr": 18446744071590143360,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 397
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:94",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596771882,
      "name": "intel_pasid_alloc_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071590457712,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 413
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel/pasid.c:37",
      "file": "drivers/iommu/intel/pasid.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597680520,
      "name": "intel_pasid_alloc_table.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071590804848,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585880256,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:122",
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
      "addr": 18446744071585880256,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585740032,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:122",
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
      "addr": 18446744071585740032,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586069904,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:122",
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
      "addr": 18446744071586069904,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
int intel_pasid_alloc_table(struct device * dev)
```

```json
{
  "name": "intel_pasid_alloc_table",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586178144,
      "name": "intel_pasid_alloc_table",
      "external": true,
      "loc": "drivers/iommu/intel-pasid.c:122",
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
      "addr": 18446744071586178144,
      "name": "intel_pasid_alloc_table",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 423
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
int intel_pasid_alloc_table(struct device * dev)
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int intel_pasid_alloc_table(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int intel_pasid_alloc_table(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int intel_pasid_alloc_table(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int intel_pasid_alloc_table(struct device * dev)
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
