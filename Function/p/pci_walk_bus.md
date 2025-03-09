# Function: <code>pci_walk_bus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583232432,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:340",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583232432,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583541280,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:380",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583541280,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583677600,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:380",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583677600,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583718016,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:380",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583718016,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583975616,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:380",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv_core.c:broadcast_error_message",
        "drivers/pci/pcie/aer/aerdrv.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583975616,
      "name": "pci_walk_bus",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584169376,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:379",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_fatal_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584169376,
      "name": "pci_walk_bus",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584257280,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:379",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584257280,
      "name": "pci_walk_bus",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584450432,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450432,
      "name": "pci_walk_bus",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584587104,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584587104,
      "name": "pci_walk_bus",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585263024,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:374",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:aer_remove",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585263024,
      "name": "pci_walk_bus",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585420704,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:374",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_reflck_attach",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585420704,
      "name": "pci_walk_bus",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585301216,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:374",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_try_bus_reset",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585301216,
      "name": "pci_walk_bus",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585758176,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:374",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585758176,
      "name": "pci_walk_bus",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586942384,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:374",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_resume_bus",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_dev_set_resettable",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_ioctl"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586942384,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588100208,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_resume_bus",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588100208,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588374944,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:400",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:pci_resume_bus",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588374944,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588670128,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:439",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:__pci_set_power_state",
        "drivers/pci/pci.c:pci_bus_set_current_state",
        "drivers/pci/pci.c:pci_resume_bus",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_resume_noirq",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/rcec.c:walk_rcec",
        "drivers/pci/pcie/aer.c:find_source_device",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588670128,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496825640,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496825640,
      "name": "pci_walk_bus",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230106368,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/irqchip/irq-gic-v3-its-pci-msi.c:its_pci_msi_prepare",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230106368,
      "name": "pci_walk_bus",
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290897600,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda1_setup_dma_pe",
        "arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda_pe_dma_weight",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290897600,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 280
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275532562,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275532562,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584539264,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584539264,
      "name": "pci_walk_bus",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584467424,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584467424,
      "name": "pci_walk_bus",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584537264,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584537264,
      "name": "pci_walk_bus",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void pci_walk_bus(struct pci_bus * top, int (*)(struct pci_dev *, void *) cb, void * userdata)
```

```json
{
  "name": "pci_walk_bus",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584645008,
      "name": "pci_walk_bus",
      "external": true,
      "loc": "drivers/pci/bus.c:378",
      "file": "drivers/pci/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/probe.c:pcie_bus_configure_settings",
        "drivers/pci/pci.c:pci_bridge_d3_update",
        "drivers/pci/pci.c:pci_pme_wakeup_bus",
        "drivers/pci/pci.c:pci_power_up",
        "drivers/pci/pci.c:pci_set_power_state",
        "drivers/pci/pci.c:__pci_complete_power_transition",
        "drivers/pci/setup-bus.c:pci_assign_unassigned_root_bus_resources",
        "drivers/pci/quirks.c:quirk_no_ext_tags",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/err.c:pcie_do_recovery",
        "drivers/pci/pcie/aer.c:set_downstream_devices_error_reporting",
        "drivers/pci/pcie/pme.c:pcie_pme_probe",
        "drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device",
        "drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_ioctl",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_disable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584645008,
      "name": "pci_walk_bus",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 144
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
