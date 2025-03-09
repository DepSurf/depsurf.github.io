# Function: <code>_dev_notice</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585782448,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3097",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info_user",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782448,
      "name": "_dev_notice",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586025510,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3351",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586025510,
      "name": "_dev_notice",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586173100,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586173100,
      "name": "_dev_notice",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586933247,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3971",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586933247,
      "name": "_dev_notice",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591485796,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:4369",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591485796,
      "name": "_dev_notice",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591429378,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:4596",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591429378,
      "name": "_dev_notice",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592487539,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:4661",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592487539,
      "name": "_dev_notice",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594357082,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:4695",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594357082,
      "name": "_dev_notice",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590261136,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:4914",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ssp_isoc_endpoint_companion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590261136,
      "name": "_dev_notice",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590580672,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:4919",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/block/virtio_blk.c:virtblk_update_capacity",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ssp_isoc_endpoint_companion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590580672,
      "name": "_dev_notice",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590938560,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:4932",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/iommu/dma-iommu.c:iommu_dma_alloc_iova",
        "drivers/block/virtio_blk.c:virtblk_update_capacity",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_bos_descriptor",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_get_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_configuration",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_interface",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_endpoint",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ss_endpoint_companion",
        "drivers/usb/core/config.c:usb_parse_ssp_isoc_endpoint_companion"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590938560,
      "name": "_dev_notice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
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
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336498969924,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/dma/mv_xor_v2.c:mv_xor_v2_probe",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu.c:arm_smmu_device_cfg_probe",
        "drivers/iommu/arm-smmu-impl.c:cavium_cfg_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/iommu/arm-smmu-v3.c:arm_smmu_device_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336498969924,
      "name": "_dev_notice",
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
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231539472,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pinctrl/sh-pfc/core.c:sh_pfc_probe",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/dma/mv_xor.c:mv_xor_probe",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/net/ethernet/ti/cpsw.c:cpsw_probe",
        "drivers/net/ethernet/ti/cpsw_ethtool.c:cpsw_set_coalesce",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231539472,
      "name": "_dev_notice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292116968,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292116968,
      "name": "_dev_notice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276349286,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276349286,
      "name": "_dev_notice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585933468,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585933468,
      "name": "_dev_notice",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585782604,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585782604,
      "name": "_dev_notice",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586123116,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586123116,
      "name": "_dev_notice",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```

```json
{
  "name": "_dev_notice",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586231724,
      "name": "_dev_notice",
      "external": true,
      "loc": "drivers/base/core.c:3503",
      "file": "drivers/base/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_r5c832",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/pci/quirks.c:ricoh_mmc_fixup_rl5c476",
        "drivers/tty/serial/serial_core.c:uart_set_info",
        "drivers/tty/serial/sccnxp.c:sccnxp_probe",
        "drivers/mfd/as3711.c:as3711_i2c_probe",
        "drivers/vfio/pci/vfio_pci.c:vfio_pci_request",
        "drivers/usb/core/hub.c:usb_root_hub_lost_power"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586231724,
      "name": "_dev_notice",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
void _dev_notice(const struct device * dev, const char * fmt, void (anon))
```
</details>
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
