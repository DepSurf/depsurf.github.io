# Function: <code>pci_find_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583279664,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:131",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/iov.c:pci_enable_sriov",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583279664,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 83
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583590752,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_create_root_bus",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583590752,
      "name": "pci_find_bus",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583727888,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583727888,
      "name": "pci_find_bus",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583768800,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:139",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583768800,
      "name": "pci_find_bus",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584028624,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:139",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584028624,
      "name": "pci_find_bus",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584225888,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:140",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584225888,
      "name": "pci_find_bus",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584315536,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:140",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584315536,
      "name": "pci_find_bus",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584510496,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:136",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584510496,
      "name": "pci_find_bus",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584646528,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584646528,
      "name": "pci_find_bus",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585331120,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:141",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585331120,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585484352,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:141",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585484352,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585364352,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:141",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585364352,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585823760,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:141",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585823760,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 223
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587014384,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:141",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587014384,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588184544,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:141",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588184544,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588460528,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:141",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588460528,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588757824,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:141",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/pme.c:pcie_pme_handle_request",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "drivers/platform/x86/p2sb.c:p2sb_bar",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588757824,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496892560,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/pci.c:raw_pci_write",
        "arch/arm64/kernel/pci.c:raw_pci_read",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496892560,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230170324,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230170324,
      "name": "pci_find_bus",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290980400,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/pci_of_scan.c:of_scan_pci_bridge",
        "arch/powerpc/platforms/powernv/eeh-powernv.c:pnv_eeh_probe",
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290980400,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 152
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275585430,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275585430,
      "name": "pci_find_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 86
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
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584597008,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584597008,
      "name": "pci_find_bus",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584526816,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584526816,
      "name": "pci_find_bus",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584596688,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584596688,
      "name": "pci_find_bus",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct pci_bus * pci_find_bus(int domain, int busnr)
```

```json
{
  "name": "pci_find_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584704384,
      "name": "pci_find_bus",
      "external": true,
      "loc": "drivers/pci/search.c:135",
      "file": "drivers/pci/search.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_hp_add_bridge",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_register_host_bridge",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/shpchp_sysfs.c:show_ctrl",
        "drivers/pci/iov.c:pci_iov_add_virtfn",
        "drivers/acpi/reboot.c:acpi_reboot",
        "arch/x86/pci/acpi.c:pci_acpi_scan_root",
        "arch/x86/pci/legacy.c:pcibios_scan_specific_bus",
        "arch/x86/pci/irq.c:pirq_peer_trick"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584704384,
      "name": "pci_find_bus",
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
