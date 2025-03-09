# Function: <code>usb_hcd_is_primary_hcd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585186464,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2634",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:hcd_release",
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_ports",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585186464,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585584521,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2638",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_ports",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585578608,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585772169,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2637",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_ports",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585766256,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585859049,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2663",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_ports",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585853120,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586298879,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2650",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_find_raw_port_number",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_ports",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586292960,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 36
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586556079,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2666",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586550512,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586705119,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2650",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586699360,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586967589,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2561",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586954240,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587166629,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587152944,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588016168,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2557",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588002352,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591544405,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2569",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588055056,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591486513,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2569",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587937872,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592564070,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2720",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548160,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594442904,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2723",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589957984,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591553785,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2717",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591547104,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591975417,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2721",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_show",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_show",
        "drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_show",
        "drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_show",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591968752,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592714425,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2696",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_calculate_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_unmap_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_map_urb_for_dma",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci-mem.c:xhci_create_secondary_interrupter",
        "drivers/usb/host/xhci-mem.c:xhci_remove_secondary_interrupter",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_usb3_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_handle_usb2_port_link_resume",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bInterfaceProtocol_show",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_bcdDevice_show",
        "drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_idProduct_show",
        "drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_idVendor_show",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592708592,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500247596,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_sch_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500229312,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232722552,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_drop_ep_quirk",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_add_ep_quirk",
        "drivers/usb/host/xhci-mtk-sch.c:xhci_mtk_sch_init",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232707652,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293541796,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293520768,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277164102,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277150316,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 58
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586872709,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586859024,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586813854,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586800512,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587121189,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587107504,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
int usb_hcd_is_primary_hcd(struct usb_hcd * hcd)
```

```json
{
  "name": "usb_hcd_is_primary_hcd",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587228305,
      "name": "usb_hcd_is_primary_hcd",
      "external": true,
      "loc": "drivers/usb/core/hcd.c:2560",
      "file": "drivers/usb/core/hcd.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/usb/core/hcd.c:usb_remove_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_add_hcd",
        "drivers/usb/core/hcd.c:usb_hc_died",
        "drivers/usb/core/hcd.c:usb_hc_died"
      ],
      "caller_func": [
        "drivers/usb/core/hcd-pci.c:usb_hcd_pci_shutdown",
        "drivers/usb/host/xhci.c:xhci_clear_tt_buffer_complete",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_gen_setup",
        "drivers/usb/host/xhci.c:xhci_get_frame",
        "drivers/usb/host/xhci.c:xhci_update_hub_device",
        "drivers/usb/host/xhci.c:xhci_disable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_enable_usb3_lpm_timeout",
        "drivers/usb/host/xhci.c:xhci_update_device",
        "drivers/usb/host/xhci.c:xhci_set_usb2_hardware_lpm",
        "drivers/usb/host/xhci.c:xhci_setup_device",
        "drivers/usb/host/xhci.c:xhci_alloc_dev",
        "drivers/usb/host/xhci.c:xhci_free_dev",
        "drivers/usb/host/xhci.c:xhci_free_streams",
        "drivers/usb/host/xhci.c:xhci_alloc_streams",
        "drivers/usb/host/xhci.c:xhci_endpoint_reset",
        "drivers/usb/host/xhci.c:xhci_endpoint_disable",
        "drivers/usb/host/xhci.c:xhci_urb_dequeue",
        "drivers/usb/host/xhci.c:xhci_urb_enqueue",
        "drivers/usb/host/xhci.c:xhci_check_args",
        "drivers/usb/host/xhci.c:xhci_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_stop",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_run",
        "drivers/usb/host/xhci.c:xhci_init",
        "drivers/usb/host/xhci.c:xhci_try_enable_msi",
        "drivers/usb/host/xhci-ring.c:xhci_irq",
        "drivers/usb/host/xhci-hub.c:xhci_get_resuming_ports",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_resume",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_bus_suspend",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_status_data",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_hub_control",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_get_port_status",
        "drivers/usb/host/xhci-hub.c:xhci_set_port_power",
        "drivers/usb/host/xhci-dbgcap.c:dbc_store",
        "drivers/usb/host/xhci-dbgcap.c:dbc_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_port_write",
        "drivers/usb/host/xhci-debugfs.c:xhci_endpoint_context_show",
        "drivers/usb/host/xhci-debugfs.c:xhci_slot_context_show",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pme_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_ssic_port_unused_quirk",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove",
        "drivers/usb/host/xhci-pci.c:xhci_pci_probe",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup",
        "drivers/usb/host/xhci-pci.c:xhci_pci_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587214832,
      "name": "usb_hcd_is_primary_hcd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 39
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
