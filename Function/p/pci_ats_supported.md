# Function: <code>pci_ats_supported</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```

```json
{
  "name": "pci_ats_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585486005,
      "name": "pci_ats_supported",
      "external": true,
      "loc": "drivers/pci/ats.c:40",
      "file": "drivers/pci/ats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485904,
      "name": "pci_ats_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```

```json
{
  "name": "pci_ats_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585618517,
      "name": "pci_ats_supported",
      "external": true,
      "loc": "drivers/pci/ats.c:40",
      "file": "drivers/pci/ats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585618416,
      "name": "pci_ats_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```

```json
{
  "name": "pci_ats_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585496965,
      "name": "pci_ats_supported",
      "external": true,
      "loc": "drivers/pci/ats.c:40",
      "file": "drivers/pci/ats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585496864,
      "name": "pci_ats_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```

```json
{
  "name": "pci_ats_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585963957,
      "name": "pci_ats_supported",
      "external": true,
      "loc": "drivers/pci/ats.c:40",
      "file": "drivers/pci/ats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:dmar_insert_one_dev_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585963856,
      "name": "pci_ats_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```

```json
{
  "name": "pci_ats_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587168965,
      "name": "pci_ats_supported",
      "external": true,
      "loc": "drivers/pci/ats.c:40",
      "file": "drivers/pci/ats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587168864,
      "name": "pci_ats_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```

```json
{
  "name": "pci_ats_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588381957,
      "name": "pci_ats_supported",
      "external": true,
      "loc": "drivers/pci/ats.c:40",
      "file": "drivers/pci/ats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588381824,
      "name": "pci_ats_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```

```json
{
  "name": "pci_ats_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588657957,
      "name": "pci_ats_supported",
      "external": true,
      "loc": "drivers/pci/ats.c:40",
      "file": "drivers/pci/ats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:amd_iommu_device_info",
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657824,
      "name": "pci_ats_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```

```json
{
  "name": "pci_ats_supported",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588958533,
      "name": "pci_ats_supported",
      "external": true,
      "loc": "drivers/pci/ats.c:41",
      "file": "drivers/pci/ats.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/ats.c:pci_enable_ats"
      ],
      "caller_func": [
        "drivers/iommu/amd/iommu.c:iommu_init_device",
        "drivers/iommu/intel/iommu.c:intel_iommu_probe_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588958400,
      "name": "pci_ats_supported",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 45
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
bool pci_ats_supported(struct pci_dev * dev)
```
</details>
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
