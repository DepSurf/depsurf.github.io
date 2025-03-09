# Function: <code>pcie_capability_read_dword</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583229232,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:684",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229232,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 150
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583537904,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:795",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537904,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583674240,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:807",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674240,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583714624,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:817",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-sysfs.c:max_link_width_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714624,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583972128,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:817",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-sysfs.c:max_link_width_show",
        "drivers/pci/pci-sysfs.c:max_link_speed_show",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972128,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584167216,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:450",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_probe_reset_function",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/pci-acpi.c:pciehp_is_native"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167216,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 159
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584255088,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:450",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584255088,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584447776,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:450",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447776,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584584496,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584496,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585260544,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:437",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pci_probe_reset_function",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585260544,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585418272,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:437",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pci_probe_reset_function",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418272,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298624,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:437",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pci_probe_reset_function",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298624,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585755584,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:437",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585755584,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 187
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586941280,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:442",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_check_latency",
        "drivers/pci/pcie/aspm.c:pcie_aspm_check_latency",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941280,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588099024,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:448",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_check_latency",
        "drivers/pci/pcie/aspm.c:pcie_aspm_check_latency",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588099024,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588373552,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:448",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_check_latency",
        "drivers/pci/pcie/aspm.c:pcie_aspm_check_latency",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373552,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668512,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:448",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pcie_get_speed_cap",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_check_latency",
        "drivers/pci/pcie/aspm.c:pcie_aspm_check_latency",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/hotplug/pciehp_hpc.c:quirk_cmd_compl",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668512,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496821160,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496821160,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 236
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230105672,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230105672,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290892256,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290892256,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 344
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275530068,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275530068,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584536656,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536656,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584464832,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464832,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584534656,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534656,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
int pcie_capability_read_dword(struct pci_dev * dev, int pos, u32 * val)
```

```json
{
  "name": "pcie_capability_read_dword",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584643968,
      "name": "pcie_capability_read_dword",
      "external": true,
      "loc": "drivers/pci/access.c:441",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_dword",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_capable",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pciehp_is_native",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643968,
      "name": "pcie_capability_read_dword",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
