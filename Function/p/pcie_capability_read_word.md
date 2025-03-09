# Function: <code>pcie_capability_read_word</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583228944,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:649",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_get_minimum_link",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583228944,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583537616,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:760",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_get_minimum_link",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583537616,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583673952,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:772",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_get_minimum_link",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583673952,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583714304,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:782",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_get_minimum_link",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583714304,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583971808,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:782",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_get_minimum_link",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aer/aerdrv.c:aer_error_resume",
        "drivers/pci/pcie/aer/aerdrv.c:aer_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583971808,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584166928,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:415",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_error_resume",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_adapter_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584166928,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584254768,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:415",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584254768,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584447584,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:415",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:program_hpp_type2",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447584,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584584304,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584584304,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585260352,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:402",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585260352,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585418080,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:402",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585418080,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585298432,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:402",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585298432,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585755392,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:402",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585755392,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586941072,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:407",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aer.c:find_device_iter",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586941072,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588098800,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:413",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:find_device_iter",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098800,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588373328,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:413",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word_locked",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link_status",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aer.c:find_device_iter",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588373328,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588668288,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:413",
      "file": "drivers/pci/access.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word_locked",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_configure_extended_tags",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_link_speed_mbps",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus",
        "drivers/pci/pci.c:pcie_wait_for_link_status",
        "drivers/pci/pci.c:pcie_clear_device_status",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pcie/portdrv.c:pcie_port_enable_irq_vec",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aspm.c:pcie_aspm_configure_common_clock",
        "drivers/pci/pcie/aer.c:find_device_iter",
        "drivers/pci/pci-acpi.c:program_hpx_type2",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/quirks.c:pcie_failed_link_retrain",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present_or_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588668288,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336496824304,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496824304,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3230105324,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230105324,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290891904,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290891904,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936275529772,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275529772,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584536464,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536464,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584464640,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584464640,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584534464,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534464,
      "name": "pcie_capability_read_word",
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
int pcie_capability_read_word(struct pci_dev * dev, int pos, u16 * val)
```

```json
{
  "name": "pcie_capability_read_word",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584643776,
      "name": "pcie_capability_read_word",
      "external": true,
      "loc": "drivers/pci/access.c:406",
      "file": "drivers/pci/access.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pcie_capability_clear_and_set_word",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcie_bandwidth_available",
        "drivers/pci/pci.c:pcie_set_readrq",
        "drivers/pci/pci.c:pcie_get_readrq",
        "drivers/pci/pci.c:pcie_wait_for_link_delay",
        "drivers/pci/pci-sysfs.c:current_link_width_show",
        "drivers/pci/pci-sysfs.c:current_link_speed_show",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/pcie/portdrv_core.c:pcie_port_device_register",
        "drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_aspm_cap_init",
        "drivers/pci/pcie/aspm.c:pcie_get_aspm_reg",
        "drivers/pci/pcie/aer.c:aer_probe",
        "drivers/pci/pcie/aer.c:pci_aer_clear_device_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_init",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_isr",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_power_on_slot",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_query_power_fault",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_card_present",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_latch_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_power_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_attention_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_get_raw_indicator_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_status",
        "drivers/pci/hotplug/pciehp_hpc.c:pciehp_check_link_active",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_do_write_cmd",
        "drivers/pci/hotplug/pciehp_hpc.c:pcie_wait_cmd"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643776,
      "name": "pcie_capability_read_word",
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
