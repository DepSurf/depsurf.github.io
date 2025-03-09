# Function: <code>__suspend_report_result</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584450352,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1682",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_prepare"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584450352,
      "name": "__suspend_report_result",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584798173,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1700",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584786480,
      "name": "__suspend_report_result",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584990109,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1775",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978272,
      "name": "__suspend_report_result",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585075394,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1778",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:legacy_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585062944,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
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
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585498329,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1871",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585485584,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 37
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585744247,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2047",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585743847,
      "name": "__suspend_report_result.cold.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585730272,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585876983,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2053",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585876583,
      "name": "__suspend_report_result.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585862976,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586114048,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2041",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586113791,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586099840,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586261413,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2062",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586261215,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586247232,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587029509,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1939",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587029286,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587014928,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591488984,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1938",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591488762,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071587099584,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591432150,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1939",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591431794,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071586986128,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592491808,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1967",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592491308,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587552288,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, struct device * dev, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594361304,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1963",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594361226,
      "name": "__suspend_report_result.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071594361281,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    },
    {
      "addr": 18446744071588885312,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 26
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
void __suspend_report_result(const char * function, struct device * dev, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590394534,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1963",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590395184,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __suspend_report_result(const char * function, struct device * dev, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590714118,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1963",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590714768,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __suspend_report_result(const char * function, struct device * dev, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591076086,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:1962",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:device_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591076736,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499081368,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2062",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499066928,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231634596,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2062",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231620280,
      "name": "__suspend_report_result",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055292262216,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2062",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292242672,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586024741,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2062",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586024543,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586008960,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585870693,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2062",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585870495,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071585856560,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586211429,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2062",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586211231,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586197248,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```

```json
{
  "name": "__suspend_report_result",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586320541,
      "name": "__suspend_report_result",
      "external": true,
      "loc": "drivers/base/power/main.c:2062",
      "file": "drivers/base/power/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/base/power/main.c:dpm_prepare",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/base/power/main.c:dpm_run_callback"
      ],
      "caller_func": [
        "drivers/pci/pci-driver.c:pci_pm_poweroff_noirq",
        "drivers/pci/pci-driver.c:pci_pm_poweroff",
        "drivers/pci/pci-driver.c:pci_pm_freeze_noirq",
        "drivers/pci/pci-driver.c:pci_pm_freeze",
        "drivers/pci/pci-driver.c:pci_pm_suspend_noirq",
        "drivers/pci/pci-driver.c:pci_pm_suspend",
        "drivers/pci/pci-driver.c:pci_legacy_suspend_late",
        "drivers/pci/pci-driver.c:pci_legacy_suspend",
        "drivers/pnp/driver.c:__pnp_bus_suspend",
        "drivers/usb/core/hcd-pci.c:hcd_pci_suspend_noirq",
        "drivers/usb/core/hcd-pci.c:suspend_common",
        "drivers/usb/core/hcd-pci.c:suspend_common"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586320303,
      "name": "__suspend_report_result.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
    },
    {
      "addr": 18446744071586305920,
      "name": "__suspend_report_result",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 19
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param reordered. </b>
<code>function, fn, ret</code> ➡️ <code>function, dev, fn, ret</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __suspend_report_result(const char * function, void * fn, int ret)
```
</details>
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
