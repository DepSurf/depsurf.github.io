# Function: <code>pm_runtime_set_autosuspend_delay</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584446544,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1351",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446544,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584782608,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1355",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782608,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584974592,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1443",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974592,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585059344,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1443",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059344,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585482176,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1435",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482176,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585725632,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1435",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725632,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585857616,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1442",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585857616,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 93
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586094816,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1526",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094816,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586242368,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586242368,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009168,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1553",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009168,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587093424,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1585",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093424,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586979632,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1585",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586979632,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587544544,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1621",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587544544,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588878160,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1660",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878160,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590386480,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1674",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590386480,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590706208,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1674",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/serial_port.c:serial_port_probe",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706208,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591068064,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1675",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/serial_port.c:serial_port_probe",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/scsi/sd.c:sd_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068064,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499058784,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/host/mmci.c:mmci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499058784,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231613564,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231613564,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292235008,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292235008,
      "name": "pm_runtime_set_autosuspend_delay",
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276415662,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276415662,
      "name": "pm_runtime_set_autosuspend_delay",
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586002576,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002576,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585851728,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851728,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586192384,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192384,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 97
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
void pm_runtime_set_autosuspend_delay(struct device * dev, int delay)
```

```json
{
  "name": "pm_runtime_set_autosuspend_delay",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586300096,
      "name": "pm_runtime_set_autosuspend_delay",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1528",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/base/power/sysfs.c:autosuspend_delay_ms_store",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/usb.c:usb_alloc_dev",
        "drivers/usb/core/hub.c:hub_probe",
        "drivers/usb/core/sysfs.c:autosuspend_store",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586300096,
      "name": "pm_runtime_set_autosuspend_delay",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
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
