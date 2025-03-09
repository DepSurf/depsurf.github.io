# Function: <code>pci_find_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583256576,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:237",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_vpd_pci22_init",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_cfg_space_size",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583256576,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583566176,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:258",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_vpd_init",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583566176,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583703072,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:258",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_vpd_init",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583703072,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583743440,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:260",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_vpd_init",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583743440,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001696,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:261",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/access.c:pci_vpd_init",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001696,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 115
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584195664,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:273",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/pci/pci-acpi.c:shpchp_is_native",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584195664,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584285104,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_configure_device",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584285104,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584479632,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:program_hpx_type3",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584479632,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584615120,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584615120,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585295120,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:471",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_msi_setup_pci_dev",
        "drivers/pci/probe.c:pci_msi_setup_pci_dev",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585295120,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
u8 pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585449856,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:480",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/msi.c:pci_msix_init",
        "drivers/pci/msi.c:pci_msi_init",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585449856,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
u8 pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585329920,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:480",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/msi.c:pci_msix_init",
        "drivers/pci/msi.c:pci_msi_init",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585329920,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
u8 pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585787536,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:490",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/msi.c:pci_msix_init",
        "drivers/pci/msi.c:pci_msi_init",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:vp_get_shm_region",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585787536,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
u8 pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586977152,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:507",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_cfg_space_size",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:_pci_add_cap_save_buffer",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msix_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msi_init",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586977152,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
u8 pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588142320,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:491",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_cfg_space_size",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:_pci_add_cap_save_buffer",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msix_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msi_init",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588142320,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
u8 pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588417872,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:506",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_cfg_space_size",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:_pci_add_cap_save_buffer",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msix_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msi_init",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588417872,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
u8 pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588713200,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:506",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/hyperv/irqdomain.c:hv_build_pci_dev_id",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:pci_cfg_space_size",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_alloc_child_bus",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/probe.c:pci_set_bus_speed",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:_pci_add_cap_save_buffer",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/pci.c:pci_save_state",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msix_init",
        "drivers/pci/msi/pcidev_msi.c:pci_msi_init",
        "drivers/pci/pci-acpi.c:acpi_run_hpx",
        "drivers/pci/pci-acpi.c:program_hpx_type3_register",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:nvbridge_check_legacy_irq_routing",
        "drivers/pci/hotplug/shpchp_core.c:shpc_probe",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern_dev.c:vp_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_find_shm_cap",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588713200,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496855232,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496855232,
      "name": "pci_find_capability",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230136176,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230136176,
      "name": "pci_find_capability",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290935840,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290935840,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275557934,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275557934,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584567280,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567280,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584495440,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495440,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584565280,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584565280,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
int pci_find_capability(struct pci_dev * dev, int cap)
```

```json
{
  "name": "pci_find_capability",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584673264,
      "name": "pci_find_capability",
      "external": true,
      "loc": "drivers/pci/pci.c:439",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_device_add",
        "drivers/pci/probe.c:pci_setup_device",
        "drivers/pci/probe.c:set_pcie_port_type",
        "drivers/pci/probe.c:pci_scan_bridge_extend",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/probe.c:pci_add_new_bus",
        "drivers/pci/pci.c:pcix_set_mmrbc",
        "drivers/pci/pci.c:pcix_get_mmrbc",
        "drivers/pci/pci.c:pcix_get_max_mmrbc",
        "drivers/pci/pci.c:pci_af_flr",
        "drivers/pci/pci.c:pci_ea_init",
        "drivers/pci/pci.c:pci_pm_init",
        "drivers/pci/vpd.c:pci_vpd_init",
        "drivers/pci/pci-acpi.c:pci_acpi_program_hp_params",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/quirks.c:quirk_intel_qat_vf_cap",
        "drivers/pci/hotplug/shpchp_hpc.c:shpc_init",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/virtio/virtio_pci_modern.c:virtio_pci_modern_probe",
        "drivers/char/agp/generic.c:agp_device_command",
        "drivers/char/agp/generic.c:agp_collect_device_status",
        "drivers/char/agp/isoch.c:agp_3_5_enable",
        "drivers/char/agp/amd64-agp.c:agp_amd64_probe",
        "drivers/char/agp/intel-agp.c:agp_intel_probe",
        "drivers/char/agp/via-agp.c:agp_via_probe",
        "drivers/usb/host/ehci-pci.c:ehci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584673264,
      "name": "pci_find_capability",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 117
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u8</code>
</li>
</ul>
</details>
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
