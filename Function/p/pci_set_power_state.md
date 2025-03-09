# Function: <code>pci_set_power_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583262224,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:856",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583262224,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 255
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583572320,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:877",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583572320,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583708912,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:902",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583708912,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583749856,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:898",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583749856,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584008880,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:901",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584008880,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584204416,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:913",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584204416,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 259
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584292720,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1084",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584292720,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 270
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584486912,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1110",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci.c:xhci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584486912,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 273
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584622512,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584622512,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585304704,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1166",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585304704,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585460944,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1300",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:pci_enable_device_flags",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585460944,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 409
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585340832,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1330",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585340832,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585797824,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1340",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585797824,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 407
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1433",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_set_power_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594226259,
      "name": "pci_set_power_state.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 43
    },
    {
      "addr": 18446744071586985648,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588152640,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1411",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588152640,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 582
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588428160,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1449",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:do_pci_enable_device",
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588428160,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 591
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588725776,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1590",
      "file": "drivers/pci/pci.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci.c:do_pci_enable_device"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_restore",
        "drivers/pci/pci-driver.c:pci_pm_resume",
        "drivers/ata/libata-core.c:ata_pci_device_resume",
        "drivers/ata/libata-core.c:ata_pci_device_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588725328,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336496866200,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336496866200,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 308
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3230144184,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3230144184,
      "name": "pci_set_power_state",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290947072,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/eeh.c:eeh_disable_and_save_dev_state",
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290947072,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 444
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275566096,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_runtime_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275566096,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 240
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584574672,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584574672,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584502832,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584502832,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584572672,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584572672,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
int pci_set_power_state(struct pci_dev * dev, pci_power_t state)
```

```json
{
  "name": "pci_set_power_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584680416,
      "name": "pci_set_power_state",
      "external": true,
      "loc": "drivers/pci/pci.c:1095",
      "file": "drivers/pci/pci.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_dev_save_and_disable",
        "drivers/pci/pci.c:pci_finish_runtime_suspend",
        "drivers/pci/pci.c:pci_back_from_sleep",
        "drivers/pci/pci.c:pci_prepare_to_sleep",
        "drivers/pci/pci-driver.c:pci_pm_thaw_noirq",
        "drivers/pci/pci-driver.c:pci_restore_standard_config",
        "drivers/char/agp/amd64-agp.c:agp_amd64_resume",
        "drivers/char/agp/amd64-agp.c:agp_amd64_suspend",
        "drivers/char/agp/via-agp.c:agp_via_resume",
        "drivers/char/agp/via-agp.c:agp_via_suspend",
        "drivers/ata/libata-core.c:ata_pci_device_do_resume",
        "drivers/ata/libata-core.c:ata_pci_device_do_suspend",
        "drivers/ata/ata_piix.c:piix_pci_device_resume",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_set_power_state",
        "drivers/usb/host/xhci-pci.c:xhci_pci_shutdown",
        "drivers/usb/host/xhci-pci.c:xhci_pci_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584680416,
      "name": "pci_set_power_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
