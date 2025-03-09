# Function: <code>pci_prg_resp_pasid_required</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584656800,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584656800,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584794320,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584794320,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585487888,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:321",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585487888,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585620400,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:322",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585620400,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585498848,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:322",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585498848,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585965856,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:322",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585965856,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587171168,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:322",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587171168,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588384432,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:322",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:iommu_enable_pci_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588384432,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588660432,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:322",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588660432,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588961008,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:323",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_pdev_enable_cap_pri",
        "drivers/iommu/intel/iommu.c:intel_iommu_dev_enable_feat"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588961008,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 43
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497062408,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497062408,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230272580,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230272580,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291102256,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291102256,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275708050,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275708050,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743072,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743072,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584673840,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584673840,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744480,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584744480,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
```

```json
{
  "name": "pci_prg_resp_pasid_required",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584852048,
      "name": "pci_prg_resp_pasid_required",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584852048,
      "name": "pci_prg_resp_pasid_required",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
int pci_prg_resp_pasid_required(struct pci_dev * pdev)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
