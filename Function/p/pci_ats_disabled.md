# Function: <code>pci_ats_disabled</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584203264,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:118",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584203264,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584291536,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584291536,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584485744,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584485744,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584621360,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584621360,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585284784,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:130",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585284784,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585439344,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:139",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439344,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585319456,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:139",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319456,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585790940,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:145",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_acs"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592363153,
      "name": "pci_ats_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 32
    },
    {
      "addr": 18446744071585782016,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978262,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:145",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_acs"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594225348,
      "name": "pci_ats_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071586971504,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588144070,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:149",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_acs"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596208026,
      "name": "pci_ats_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588136352,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588419622,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:164",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_acs"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596733154,
      "name": "pci_ats_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588411600,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588714374,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:164",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_enable_acs"
      ],
      "caller_func": [
        "drivers/pci/quirks.c:pci_quirk_enable_intel_spt_pch_acs",
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597641610,
      "name": "pci_ats_disabled.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
    },
    {
      "addr": 18446744071588706880,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496864832,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_attach_dev"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496864832,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230142824,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230142824,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290945184,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290945184,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275565050,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275565050,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 34
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584573520,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584573520,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584501680,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584501680,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584571520,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584571520,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
bool pci_ats_disabled()
```

```json
{
  "name": "pci_ats_disabled",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584679264,
      "name": "pci_ats_disabled",
      "external": true,
      "loc": "drivers/pci/pci.c:122",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/ats.c:pci_ats_init",
        "drivers/iommu/amd_iommu.c:amd_iommu_device_info",
        "drivers/iommu/intel-iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584679264,
      "name": "pci_ats_disabled",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
bool pci_ats_disabled()
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
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
