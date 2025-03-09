# Function: <code>pcie_capability_write_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583228688,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:712",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228688,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 125
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537376,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:823",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537376,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583673712,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:835",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673712,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 113
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583714048,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:845",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714048,
      "name": "pcie_capability_write_word",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583971552,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:845",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971552,
      "name": "pcie_capability_write_word",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584166608,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:478",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aer.c:aer_error_resume",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_reenable_notification",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166608,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 149
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584254512,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:478",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254512,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584447968,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:478",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447968,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584584688,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584688,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585260736,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:465",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585260736,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585418464,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:465",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/pci.c:pci_restore_pcie_state",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418464,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298816,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:465",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298816,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585755776,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:465",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585755776,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586941488,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:470",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941488,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588099248,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:476",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588099248,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588373776,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:476",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word_locked",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373776,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588668736,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:476",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word_locked",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_slot_reset",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_ist",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668736,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 167
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496823744,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496823744,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230105084,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230105084,
      "name": "pcie_capability_write_word",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290892608,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290892608,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275529528,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275529528,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 122
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584536848,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536848,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584465024,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465024,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584534848,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534848,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
int pcie_capability_write_word(struct pci_dev * dev, int pos, u16 val)
```

```json
{
  "name": "pcie_capability_write_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584644160,
      "name": "pcie_capability_write_word",
      "external": true,
      "loc": "drivers/pci/access.c:469",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_reset_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_clear_hotplug_events",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644160,
      "name": "pcie_capability_write_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 110
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
