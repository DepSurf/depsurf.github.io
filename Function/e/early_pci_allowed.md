# Function: <code>early_pci_allowed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586163168,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:53",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586163168,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586576709,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:53",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586576480,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586758277,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:53",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586758048,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586885189,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:53",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586884960,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587373877,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587373648,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587677509,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:54",
      "file": "arch/x86/pci/early.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/pci/early.c:early_dump_pci_devices"
      ],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587677472,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587809008,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587809008,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588114496,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114496,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588320192,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588320192,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591140528,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591140528,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591224752,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591224752,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591173984,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591173984,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592027504,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592027504,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593794672,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593794672,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595737968,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595737968,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596263952,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596263952,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597146608,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:early_reserve_memory",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597146608,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587923840,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587923840,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587639696,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587639696,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588257248,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588257248,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
int early_pci_allowed()
```

```json
{
  "name": "early_pci_allowed",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588392768,
      "name": "early_pci_allowed",
      "external": true,
      "loc": "arch/x86/pci/early.c:79",
      "file": "arch/x86/pci/early.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/setup.c:setup_arch",
        "arch/x86/kernel/early-quirks.c:early_quirks",
        "arch/x86/kernel/aperture_64.c:gart_iommu_hole_init",
        "arch/x86/kernel/aperture_64.c:early_gart_iommu_check",
        "arch/x86/kernel/pci-calgary_64.c:detect_calgary",
        "arch/x86/kernel/mmconf-fam10h_64.c:get_fam10h_pci_mmconf_base",
        "arch/x86/kernel/vsmp_64.c:vsmp_init",
        "arch/x86/mm/amdtopology.c:amd_numa_init",
        "drivers/usb/early/ehci-dbgp.c:early_dbgp_init",
        "drivers/usb/early/xhci-dbc.c:early_xdbc_parse_parameter",
        "arch/x86/pci/amd_bus.c:amd_postcore_init",
        "arch/x86/pci/amd_bus.c:early_root_info_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588392768,
      "name": "early_pci_allowed",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int early_pci_allowed()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int early_pci_allowed()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int early_pci_allowed()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int early_pci_allowed()
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
