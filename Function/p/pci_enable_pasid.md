# Function: <code>pci_enable_pasid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583390400,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:237",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390400,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583704816,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:237",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583704816,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583843136,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:237",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel-iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583843136,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583884640,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:266",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:amd_iommu_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583884640,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584147424,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:266",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu.c:attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584147424,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584364272,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:268",
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
      "addr": 18446744071584364272,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584459376,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:268",
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
      "addr": 18446744071584459376,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
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
      "addr": 18446744071584657818,
      "name": "pci_enable_pasid.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071584656496,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584794016,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
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
      "addr": 18446744071584794016,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585486528,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:360",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:pdev_iommuv2_enable",
        "drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585486528,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585619040,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:361",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:pdev_iommuv2_enable",
        "drivers/iommu/intel/iommu.c:iommu_enable_dev_iotlb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585619040,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585497488,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:361",
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
      "addr": 18446744071585497488,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585964480,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:361",
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
      "addr": 18446744071585964480,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587169600,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:361",
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
      "addr": 18446744071587169600,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 235
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588382960,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:361",
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
      "addr": 18446744071588382960,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588658960,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:361",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:attach_device",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588658960,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588959536,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:362",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_attach_device",
        "drivers/iommu/intel/iommu.c:dmar_domain_attach_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588959536,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 258
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497062056,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497062056,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230272200,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230272200,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291101760,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291101760,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 336
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275707802,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
      "file": "drivers/pci/ats.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275707802,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 174
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584742768,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
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
      "addr": 18446744071584742768,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584673536,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
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
      "addr": 18446744071584673536,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584744176,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
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
      "addr": 18446744071584744176,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pci_enable_pasid(struct pci_dev * pdev, int features)
```

```json
{
  "name": "pci_enable_pasid",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584851744,
      "name": "pci_enable_pasid",
      "external": true,
      "loc": "drivers/pci/ats.c:295",
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
      "addr": 18446744071584851744,
      "name": "pci_enable_pasid",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
