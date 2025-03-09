# Function: <code>pcie_port_find_device</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584286912,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:456",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584286912,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584380416,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:476",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584380416,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584577264,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:484",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584577264,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584714352,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:489",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584714352,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585368480,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:468",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585368480,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585526960,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:465",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585526960,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585405344,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:465",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585405344,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585866816,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:470",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585866816,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587060432,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:470",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587060432,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588245312,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv.c:478",
      "file": "drivers/pci/pcie/portdrv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588245312,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588520864,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv.c:478",
      "file": "drivers/pci/pcie/portdrv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588520864,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588819456,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv.c:479",
      "file": "drivers/pci/pcie/portdrv.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588819456,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496972984,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:489",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496972984,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 116
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230237176,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:489",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230237176,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275641500,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:489",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275641500,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664832,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:489",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664832,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593984,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:489",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593984,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584664512,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:489",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584664512,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```

```json
{
  "name": "pcie_port_find_device",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584772208,
      "name": "pcie_port_find_device",
      "external": true,
      "loc": "drivers/pci/pcie/portdrv_core.c:489",
      "file": "drivers/pci/pcie/portdrv_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/dpc.c:dpc_reset_link",
        "drivers/pci/pcie/dpc.c:pci_restore_dpc_state",
        "drivers/pci/pcie/dpc.c:pci_save_dpc_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584772208,
      "name": "pcie_port_find_device",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
```
</details>
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
struct device * pcie_port_find_device(struct pci_dev * dev, u32 service)
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
