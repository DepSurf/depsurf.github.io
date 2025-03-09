# Function: <code>__pm_runtime_use_autosuspend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584446640,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1372",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_pm_runtime_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584446640,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584782704,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1376",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584782704,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584974688,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1464",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-core.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584974688,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585059440,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1464",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059440,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585482272,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1456",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585482272,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585725728,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1456",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585725728,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585857712,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1463",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585857712,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586094928,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1547",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586094928,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586242480,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586242480,
      "name": "__pm_runtime_use_autosuspend",
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587009280,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1574",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587009280,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587093536,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1606",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093536,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586979744,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1606",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586979744,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587544656,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1642",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587544656,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588878527,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1681",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:devm_pm_runtime_enable"
      ],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588878256,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590386895,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1695",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:devm_pm_runtime_enable"
      ],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590386592,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590706630,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1695",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:devm_pm_runtime_enable"
      ],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/serial_port.c:serial_port_remove",
        "drivers/tty/serial/serial_port.c:serial_port_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590706320,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591068486,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1696",
      "file": "drivers/base/power/runtime.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/runtime.c:devm_pm_runtime_enable"
      ],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_shutdown",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_remove",
        "drivers/pci/pcie/portdrv.c:pcie_portdrv_probe",
        "drivers/tty/serial/serial_port.c:serial_port_remove",
        "drivers/tty/serial/serial_port.c:serial_port_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591068176,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499058960,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_remove",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-sprd.c:sprd_i2c_probe",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/host/mmci.c:mmci_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499058960,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231613656,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/tty/serial/omap-serial.c:serial_omap_remove",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/tty/serial/omap-serial.c:serial_omap_probe",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_remove",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/spi/spi-omap2-mcspi.c:omap2_mcspi_probe",
        "drivers/net/ethernet/freescale/fec_main.c:fec_probe",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_remove",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/net/ethernet/ti/davinci_mdio.c:davinci_mdio_probe",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/usb/musb/musb_core.c:musb_remove",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/usb/musb/musb_core.c:musb_init_controller",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-imx.c:i2c_imx_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_remove",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/i2c/busses/i2c-omap.c:omap_i2c_probe",
        "drivers/mmc/core/block.c:mmc_blk_probe",
        "drivers/mmc/host/mmci.c:mmci_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_remove",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_probe",
        "drivers/mmc/host/sdhci-esdhc-imx.c:sdhci_esdhc_imx_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231613656,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292235184,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292235184,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276415806,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe",
        "drivers/mmc/core/block.c:mmc_blk_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276415806,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586002688,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586002688,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585851824,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851824,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
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
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586192496,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-amd-mp2-pci.c:amd_mp2_pci_probe",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586192496,
      "name": "__pm_runtime_use_autosuspend",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void __pm_runtime_use_autosuspend(struct device * dev, bool use)
```

```json
{
  "name": "__pm_runtime_use_autosuspend",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586300192,
      "name": "__pm_runtime_use_autosuspend",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1549",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/blk-pm.c:blk_pm_runtime_init",
        "drivers/pci/pcie/portdrv_pci.c:pcie_portdrv_remove",
        "drivers/mfd/arizona-core.c:arizona_dev_init",
        "drivers/usb/core/hub.c:usb_new_device",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_remove",
        "drivers/i2c/busses/i2c-designware-platdrv.c:dw_i2c_plat_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586300192,
      "name": "__pm_runtime_use_autosuspend",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
