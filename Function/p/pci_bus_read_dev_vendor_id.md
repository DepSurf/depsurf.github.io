# Function: <code>pci_bus_read_dev_vendor_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int crs_timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583234640,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:1547",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_device_is_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583234640,
      "name": "pci_bus_read_dev_vendor_id",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int crs_timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583543728,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:1569",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_device_is_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543728,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int crs_timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583680048,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:1716",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583680048,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int crs_timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583720704,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:1870",
      "file": "drivers/pci/probe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583720704,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 201
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583978656,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2023",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583978656,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 355
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2171",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584187660,
      "name": "pci_bus_read_dev_vendor_id.cold.44",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    },
    {
      "addr": 18446744071584172464,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584268592,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2275",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268592,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584459472,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2501",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584459472,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584594784,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594784,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585272544,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2307",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_update_current_state",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585272544,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585431120,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2314",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_update_current_state",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585431120,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585311376,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2357",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_update_current_state",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585311376,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585767280,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2404",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pci_update_current_state",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585767280,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586952560,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2379",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586952560,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588114512,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2391",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_device_is_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588114512,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588389584,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2402",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_device_is_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588389584,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588685520,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2451",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_device_is_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588685520,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496836792,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496836792,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230117240,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3230117240,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290910336,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290910336,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275542372,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275542372,
      "name": "pci_bus_read_dev_vendor_id",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546944,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546944,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584475104,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584475104,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584544944,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584544944,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
bool pci_bus_read_dev_vendor_id(struct pci_bus * bus, int devfn, u32 * l, int timeout)
```

```json
{
  "name": "pci_bus_read_dev_vendor_id",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584652688,
      "name": "pci_bus_read_dev_vendor_id",
      "external": true,
      "loc": "drivers/pci/probe.c:2239",
      "file": "drivers/pci/probe.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:get_slot_status",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584652688,
      "name": "pci_bus_read_dev_vendor_id",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 46
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
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>int timeout</code>
</li>
<li>
<b>Param removed. </b>
<code>int crs_timeout</code>
</li>
</ul>
</details>
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
