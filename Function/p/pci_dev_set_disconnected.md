# Function: <code>pci_dev_set_disconnected</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583843843,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:278",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071583861670,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:278",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583842864,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071583861184,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584107294,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:281",
      "file": "drivers/pci/pcie/pcie-dpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584125286,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:281",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584105600,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071584124784,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584288664,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:293",
      "file": "drivers/pci/pcie/err.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584325794,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:293",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071584350133,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:293",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584287648,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071584325328,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071584349280,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584420320,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:352",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584446651,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:352",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584420320,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584444704,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584616800,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:357",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584643306,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:357",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584616800,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584641376,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584754784,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584780970,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754784,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584779056,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585445856,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:396",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585472309,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:396",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585445856,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071585470432,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585594208,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:379",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585614069,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:379",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585594208,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071585612192,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585472608,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:372",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585492517,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:372",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585472608,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071585490640,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585938864,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:393",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071585959333,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:393",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585938864,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071585957536,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587141856,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:354",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071587164156,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:354",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587141856,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    },
    {
      "addr": 18446744071587162192,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588346080,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:354",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588375292,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:354",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588346080,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588374352,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588622288,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:352",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588651244,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:352",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588622288,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588650768,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588745008,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:363",
      "file": "drivers/pci/pci-driver.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588922464,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:363",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071588951692,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:363",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588745008,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588922464,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071588951216,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497018112,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336497046908,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497018112,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    },
    {
      "addr": 18446603336497044728,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275677498,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275677498,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584703600,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584729722,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584703600,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584727872,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584634368,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584660490,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584634368,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584658640,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584704944,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584731130,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704944,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584729216,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Duplicate, Selective Inline ❓</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```

```json
{
  "name": "pci_dev_set_disconnected",
  "collision_type": "Static Duplication",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584812592,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/pciehp_pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584838698,
      "name": "pci_dev_set_disconnected",
      "external": false,
      "loc": "drivers/pci/pci.h:391",
      "file": "drivers/pci/hotplug/acpiphp_glue.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584812592,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446744071584836784,
      "name": "pci_dev_set_disconnected",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int pci_dev_set_disconnected(struct pci_dev * dev, void * unused)
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
