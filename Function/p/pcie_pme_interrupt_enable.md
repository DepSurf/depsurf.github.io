# Function: <code>pcie_pme_interrupt_enable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583348471,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:62",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583349088,
      "name": "pcie_pme_interrupt_enable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583350496,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583661592,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:62",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583661040,
      "name": "pcie_pme_interrupt_enable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583662464,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583798984,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:61",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583798576,
      "name": "pcie_pme_interrupt_enable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583799856,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583841969,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:55",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583841568,
      "name": "pcie_pme_interrupt_enable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071583842816,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584104689,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:55",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584104288,
      "name": "pcie_pme_interrupt_enable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584105552,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584304958,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:51",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584304592,
      "name": "pcie_pme_interrupt_enable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584306080,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584400862,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:51",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584400496,
      "name": "pcie_pme_interrupt_enable.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584401744,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584597713,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596336,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584597776,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584735537,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584734160,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584735600,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585389457,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585390032,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585546785,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585547360,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585425041,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585425616,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585889937,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585890672,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587086801,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587087760,
      "name": "pcie_pme_interrupt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588274369,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:get_port_device_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588275840,
      "name": "pcie_pme_interrupt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588550001,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:get_port_device_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588551472,
      "name": "pcie_pme_interrupt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588849617,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:54",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv.c:get_port_device_capability"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588851136,
      "name": "pcie_pme_interrupt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496996428,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496995256,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336496997440,
      "name": "pcie_pme_interrupt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230256984,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230256884,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 3230258168,
      "name": "pcie_pme_interrupt_enable",
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275661128,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275659426,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
    },
    {
      "addr": 18446743936275661238,
      "name": "pcie_pme_interrupt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
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
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584684337,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584682960,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584684400,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584615137,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584613792,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584615184,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584685697,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584684320,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584685760,
      "name": "pcie_pme_interrupt_enable",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```

```json
{
  "name": "pcie_pme_interrupt_enable",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584792417,
      "name": "pcie_pme_interrupt_enable",
      "external": true,
      "loc": "drivers/pci/pcie/pme.c:53",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": [
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584792336,
      "name": "pcie_pme_interrupt_enable.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071584793408,
      "name": "pcie_pme_interrupt_enable",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void pcie_pme_interrupt_enable(struct pci_dev * dev, bool enable)
```
</details>
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
