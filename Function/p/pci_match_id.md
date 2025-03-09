# Function: <code>pci_match_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583277904,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:222",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:store_new_id",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583277904,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583588960,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:222",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:store_new_id",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583588960,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583726112,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:222",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "arch/x86/platform/atom/pmc_atom.c:pmc_atom_init",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:store_new_id",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583726112,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583767303,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:222",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583766928,
      "name": "pci_match_id.part.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071583767056,
      "name": "pci_match_id",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584027111,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:222",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584026736,
      "name": "pci_match_id.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    },
    {
      "addr": 18446744071584026864,
      "name": "pci_match_id",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584223477,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223104,
      "name": "pci_match_id.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584223232,
      "name": "pci_match_id",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584314309,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313120,
      "name": "pci_match_id.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
    },
    {
      "addr": 18446744071584313248,
      "name": "pci_match_id",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584509222,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584508048,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584508176,
      "name": "pci_match_id",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584645254,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644080,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584644208,
      "name": "pci_match_id",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585325590,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_aspm",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585325216,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071585325344,
      "name": "pci_match_id",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585478950,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:104",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_aspm",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585478576,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071585478704,
      "name": "pci_match_id",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585358550,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:104",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585358176,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071585358304,
      "name": "pci_match_id",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585817846,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:104",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/quirks.c:pci_fixup_enable_vmd_nvme_ltr",
        "drivers/pci/quirks.c:pci_fixup_enable_aspm",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585817472,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071585817600,
      "name": "pci_match_id",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587008576,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:105",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008576,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588178304,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:105",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588178304,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588454304,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:105",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588454304,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588750992,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:105",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/clk/x86/clk-fch.c:fch_clk_remove",
        "drivers/clk/x86/clk-fch.c:fch_clk_probe",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/dwc2/params.c:dwc2_init_params",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588750992,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496890880,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496888936,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 18446603336496889152,
      "name": "pci_match_id",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230168468,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230167940,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
    },
    {
      "addr": 3230168152,
      "name": "pci_match_id",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290977460,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290976528,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    },
    {
      "addr": 13835058055290976752,
      "name": "pci_match_id",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275584254,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275582988,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446743936275583140,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595734,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594560,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584594688,
      "name": "pci_match_id",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584525542,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584524368,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584524496,
      "name": "pci_match_id",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584595414,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594240,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584594368,
      "name": "pci_match_id",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
const struct pci_device_id * pci_match_id(const struct pci_device_id * ids, struct pci_dev * dev)
```

```json
{
  "name": "pci_match_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584702662,
      "name": "pci_match_id",
      "external": true,
      "loc": "drivers/pci/pci-driver.c:221",
      "file": "drivers/pci/pci-driver.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store"
      ],
      "caller_func": [
        "arch/x86/kernel/amd_nb.c:next_northbridge",
        "drivers/pci/pci-driver.c:pci_match_device",
        "drivers/pci/pci-driver.c:new_id_store",
        "drivers/pci/quirks.c:quirk_fixed_dma_alias",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_one",
        "drivers/tty/serial/8250/8250_pci.c:pciserial_init_ports",
        "drivers/vfio/pci/vfio_pci_config.c:vfio_config_init",
        "drivers/usb/host/ehci-pci.c:ehci_pci_probe",
        "drivers/usb/host/ohci-pci.c:ohci_pci_reset",
        "drivers/platform/x86/pmc_atom.c:pmc_atom_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584702288,
      "name": "pci_match_id.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
    },
    {
      "addr": 18446744071584702416,
      "name": "pci_match_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
