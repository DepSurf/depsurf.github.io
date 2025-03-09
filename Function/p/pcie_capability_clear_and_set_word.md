# Function: <code>pcie_capability_clear_and_set_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583229104,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:736",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583229104,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583537776,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:847",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537776,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583674112,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:859",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583674112,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583714496,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:869",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_flr",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714496,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583972000,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:869",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_flr",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv_core.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583972000,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 121
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584167088,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:502",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_flr",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584167088,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584254960,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:502",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254960,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584448080,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:502",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:program_hpp_type2",
        "drivers/pci/probe.c:program_hpp_type2",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584448080,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584584800,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584800,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585260880,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:489",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm",
        "drivers/pci/pcie/aer.c:aer_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585260880,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585418624,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:489",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_l1ss",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418624,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298976,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:489",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298976,
      "name": "pcie_capability_clear_and_set_word",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585755936,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:489",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585755936,
      "name": "pcie_capability_clear_and_set_word",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586941664,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:494",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv_core.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941664,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588099440,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:500",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr",
        "drivers/pci/pcie/portdrv.c:get_port_device_capability",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588099440,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588389083,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588413115,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_retrain_link",
        "drivers/pci/pci.c:pcie_retrain_link",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588522928,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/pcie/portdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv.c:get_port_device_capability"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588529481,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588542054,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588550001,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588564957,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/pci-acpi.c:program_hpx_type2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588591869,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588628389,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1242",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588685019,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/probe.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_ltr",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_scan_bridge_extend"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588708507,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/pci.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_retrain_link",
        "drivers/pci/pci.c:pcie_retrain_link",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_bridge_reconfigure_ltr"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588821520,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/pcie/portdrv.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/portdrv.c:get_port_device_capability"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588826541,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/pcie/aspm.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588843963,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/pcie/aer.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/aer.c:pci_aer_init"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588849617,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/pcie/pme.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pcie/pme.c:pcie_pme_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_resume",
        "drivers/pci/pcie/pme.c:pcie_pme_suspend",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/pcie/pme.c:pcie_pme_work_fn"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588864781,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/pci-acpi.c:program_hpx_type2"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588900813,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/quirks.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ],
      "caller_func": []
    },
    {
      "addr": 18446744071588928565,
      "name": "pcie_capability_clear_and_set_word",
      "external": false,
      "loc": "include/linux/pci.h:1270",
      "file": "drivers/pci/hotplug/pciehp_hpc.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496824544,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496824544,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230105528,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq",
        "drivers/pci/controller/pci-tegra.c:tegra_pcie_relax_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230105528,
      "name": "pcie_capability_clear_and_set_word",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290892864,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290892864,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275529948,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275529948,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 120
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536960,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536960,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584465136,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584465136,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534960,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534960,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```

```json
{
  "name": "pcie_capability_clear_and_set_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584644272,
      "name": "pcie_capability_clear_and_set_word",
      "external": true,
      "loc": "drivers/pci/access.c:493",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/pci.c:pcie_set_mps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_enable_atomic_ops_to_root",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci.c:pci_configure_ari",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_chelsio_T5_disable_root_port_attributes",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_config_aspm_link",
        "drivers/pci/pcie/aspm.c:pcie_set_clkpm_nocheck",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_disable_pcie_error_reporting",
        "drivers/pci/pcie/aer.c:pci_enable_pcie_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_disable_interrupt",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pme.c:pcie_pme_irq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584644272,
      "name": "pcie_capability_clear_and_set_word",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 123
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int pcie_capability_clear_and_set_word(struct pci_dev * dev, int pos, u16 clear, u16 set)
```
</details>
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
