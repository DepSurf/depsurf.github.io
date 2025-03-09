# Function: <code>pci_disable_pasid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583389920,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:271",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583389920,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704336,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:271",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704336,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583842656,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:271",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842656,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884320,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:300",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884320,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584147104,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:300",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147104,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584363936,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:302",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584363936,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584459040,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:305",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459040,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584657780,
      "name": "pci_disable_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
    },
    {
      "addr": 18446744071584656064,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584793584,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584793584,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585486160,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:406",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device",
        "drivers/iommu/amd/iommu.c:pdev_iommuv2_enable",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486160,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585618672,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:407",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device",
        "drivers/iommu/amd/iommu.c:pdev_iommuv2_enable",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618672,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585497120,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:407",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585497120,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964112,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:407",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585964112,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587169136,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:407",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587169136,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588382144,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:iommu_disable_pci_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588382144,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588658144,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:410",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device",
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:iommu_disable_pci_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588658144,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588958720,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:411",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:detach_device",
        "drivers/iommu/intel/iommu.c:iommu_disable_pci_caps"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958720,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497061512,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497061512,
      "name": "pci_disable_pasid",
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230271620,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230271620,
      "name": "pci_disable_pasid",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291100976,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291100976,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275707384,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275707384,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584742336,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584742336,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584673104,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584673104,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584743744,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584743744,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void pci_disable_pasid(struct pci_dev * pdev)
```

```json
{
  "name": "pci_disable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584851312,
      "name": "pci_disable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:332",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:detach_device",
        "drivers/iommu/amd_iommu.c:attach_device",
        "drivers/iommu/intel-iommu.c:__dmar_remove_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584851312,
      "name": "pci_disable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
