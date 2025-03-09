# Function: <code>pci_restore_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583260384,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1121",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583260384,
      "name": "pci_restore_state.part.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 585
    },
    {
      "addr": 18446744071583260976,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583571066,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1142",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583570448,
      "name": "pci_restore_state.part.36",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
    },
    {
      "addr": 18446744071583571024,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583707466,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1167",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583706848,
      "name": "pci_restore_state.part.38",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 569
    },
    {
      "addr": 18446744071583707424,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583747938,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1163",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_default_resume_early",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583747296,
      "name": "pci_restore_state.part.39",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071583747872,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584006962,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1166",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_default_resume_early",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006320,
      "name": "pci_restore_state.part.40",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 563
    },
    {
      "addr": 18446744071584006896,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 27
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584202422,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1216",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_default_resume_early",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584201376,
      "name": "pci_restore_state.part.42",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 970
    },
    {
      "addr": 18446744071584202352,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584300246,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1388",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_default_resume_early",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584299216,
      "name": "pci_restore_state.part.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 954
    },
    {
      "addr": 18446744071584300176,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584494070,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1457",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584492960,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1037
    },
    {
      "addr": 18446744071584494000,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584629686,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584628528,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
    },
    {
      "addr": 18446744071584629616,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311734,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1522",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585310992,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 658
    },
    {
      "addr": 18446744071585311664,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585457062,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1657",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585456320,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    },
    {
      "addr": 18446744071585456992,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585337270,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1687",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585336224,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 968
    },
    {
      "addr": 18446744071585337200,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585800665,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1722",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585799840,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 742
    },
    {
      "addr": 18446744071592364113,
      "name": "pci_restore_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071585800592,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586988649,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1785",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_disable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586987808,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 751
    },
    {
      "addr": 18446744071594226358,
      "name": "pci_restore_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071586988560,
      "name": "pci_restore_state",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588155769,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1761",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588154928,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
    },
    {
      "addr": 18446744071596208534,
      "name": "pci_restore_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071588155664,
      "name": "pci_restore_state",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588431289,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1799",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588430448,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
    },
    {
      "addr": 18446744071596733692,
      "name": "pci_restore_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071588431184,
      "name": "pci_restore_state",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588727945,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1896",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_slot_reset",
        "drivers/pci/quirks.c:reset_chelsio_generic_dev",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588727104,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
    },
    {
      "addr": 18446744071597642115,
      "name": "pci_restore_state.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071588727840,
      "name": "pci_restore_state",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496875300,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496874048,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1152
    },
    {
      "addr": 18446603336496875200,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230152692,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230151416,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1184
    },
    {
      "addr": 3230152600,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290958788,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "arch/powerpc/kernel/eeh.c:eeh_restore_dev_state",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290957296,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1380
    },
    {
      "addr": 13835058055290958688,
      "name": "pci_restore_state",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275574042,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275572808,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1140
    },
    {
      "addr": 18446743936275573948,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584581846,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/nvme/host/pci.c:nvme_slot_reset",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584580688,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
    },
    {
      "addr": 18446744071584581776,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584509974,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/nvme/host/pci.c:nvme_slot_reset",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584508816,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
    },
    {
      "addr": 18446744071584509904,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584579846,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584578688,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
    },
    {
      "addr": 18446744071584579776,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void pci_restore_state(struct pci_dev * dev)
```

```json
{
  "name": "pci_restore_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584687558,
      "name": "pci_restore_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1453",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_restore"
      ],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci.c:pci_dev_restore",
        "drivers/pci/pci-driver.c:pci_pm_restore_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_slot_reset",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584686400,
      "name": "pci_restore_state.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1073
    },
    {
      "addr": 18446744071584687488,
      "name": "pci_restore_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
