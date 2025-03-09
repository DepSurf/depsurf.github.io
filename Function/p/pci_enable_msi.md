# Function: <code>pci_enable_msi</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583880688,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1073",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583880688,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584144176,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1073",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584144176,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584360992,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1072",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584360992,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584456176,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1078",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584456176,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584652944,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1106",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652944,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584789184,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584789184,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585481120,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481120,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585523184,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1131",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585523184,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585401360,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1137",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585401360,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585861232,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1045",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585861232,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 35
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587054480,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi/msi.c:912",
      "file": "drivers/pci/msi/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587054480,
      "name": "pci_enable_msi",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588233440,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi/api.c:30",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588233440,
      "name": "pci_enable_msi",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588508944,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi/api.c:30",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588508944,
      "name": "pci_enable_msi",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588807536,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi/api.c:30",
      "file": "drivers/pci/msi/api.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd/init.c:amd_iommu_enable_interrupts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588807536,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 47
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497056328,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497056328,
      "name": "pci_enable_msi",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230266416,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230266416,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055291094128,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055291094128,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275702770,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275702770,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584737936,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584737936,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584668704,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584668704,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739344,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739344,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
int pci_enable_msi(struct pci_dev * dev)
```

```json
{
  "name": "pci_enable_msi",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584846912,
      "name": "pci_enable_msi",
      "external": true,
      "loc": "drivers/pci/msi.c:1107",
      "file": "drivers/pci/msi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/iommu/amd_iommu_init.c:iommu_init_msi"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584846912,
      "name": "pci_enable_msi",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
int pci_enable_msi(struct pci_dev * dev)
```
</details>
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
