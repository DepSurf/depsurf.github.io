# Function: <code>pci_stop_and_remove_bus_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583249056,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:111",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_enable_sriov"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583249056,
      "name": "pci_stop_and_remove_bus_device",
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
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583558466,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:115",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583558416,
      "name": "pci_stop_and_remove_bus_device",
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
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583695330,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:115",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583695280,
      "name": "pci_stop_and_remove_bus_device",
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
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583735826,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:115",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583735776,
      "name": "pci_stop_and_remove_bus_device",
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
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583994482,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:115",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583994432,
      "name": "pci_stop_and_remove_bus_device",
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
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584188930,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:117",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584188880,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584277618,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584277568,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584472099,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584472048,
      "name": "pci_stop_and_remove_bus_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584607379,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584607328,
      "name": "pci_stop_and_remove_bus_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585284755,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585284688,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585439315,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585439248,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585319427,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:116",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585319360,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585775315,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:115",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585775248,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586961394,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:115",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586961328,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588125010,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:115",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588124928,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588400290,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:115",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "drivers/platform/x86/p2sb.c:p2sb_bar"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588400208,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588696274,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:116",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/platform/x86/p2sb.c:p2sb_scan_and_cache_devfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588696192,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496846668,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496846584,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230126684,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230126616,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290923448,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "arch/powerpc/kernel/eeh_driver.c:eeh_rmv_device",
        "arch/powerpc/kernel/pci-hotplug.c:pci_hp_remove_devices",
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290923344,
      "name": "pci_stop_and_remove_bus_device",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275550714,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275550632,
      "name": "pci_stop_and_remove_bus_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584559539,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584559488,
      "name": "pci_stop_and_remove_bus_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584487699,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584487648,
      "name": "pci_stop_and_remove_bus_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584557539,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584557488,
      "name": "pci_stop_and_remove_bus_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void pci_stop_and_remove_bus_device(struct pci_dev * dev)
```

```json
{
  "name": "pci_stop_and_remove_bus_device",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584665283,
      "name": "pci_stop_and_remove_bus_device",
      "external": true,
      "loc": "drivers/pci/remove.c:114",
      "file": "drivers/pci/remove.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/remove.c:pci_stop_and_remove_bus_device_locked"
      ],
      "caller_func": [
        "drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_unconfigure_slot",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/shpchp_pci.c:shpchp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/pci/hotplug/acpiphp_glue.c:disable_slot",
        "drivers/pci/hotplug/acpiphp_glue.c:enable_slot",
        "drivers/pci/iov.c:pci_iov_remove_virtfn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665232,
      "name": "pci_stop_and_remove_bus_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 31
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
