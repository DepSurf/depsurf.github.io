# Function: <code>pm_runtime_barrier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584447296,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1132",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset",
        "drivers/usb/core/hub.c:hub_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584447296,
      "name": "pm_runtime_barrier",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584783376,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1136",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584783376,
      "name": "pm_runtime_barrier",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584972768,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1224",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584972768,
      "name": "pm_runtime_barrier",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585058592,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1224",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585058592,
      "name": "pm_runtime_barrier",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585481424,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1209",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585481424,
      "name": "pm_runtime_barrier",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585724704,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1209",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585724704,
      "name": "pm_runtime_barrier",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585856688,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1216",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585856688,
      "name": "pm_runtime_barrier",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586093984,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1292",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586093984,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586241536,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586241536,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587008192,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1315",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587008192,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587093648,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1347",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587093648,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586979856,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1347",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586979856,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587543408,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1366",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587543408,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588877264,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1395",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588877264,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590385520,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1408",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590385520,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590705312,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1408",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590705312,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 146
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591067168,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1409",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:__driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591067168,
      "name": "pm_runtime_barrier",
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336499057400,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499057400,
      "name": "pm_runtime_barrier",
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3231613928,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_pm_barrier_for_all_ports"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3231613928,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055292230656,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_pm_barrier_for_all_ports"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055292230656,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936276414688,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_pm_barrier_for_all_ports"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276414688,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 204
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586001744,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586001744,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585850928,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850928,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 139
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586191552,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586191552,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 145
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
int pm_runtime_barrier(struct device * dev)
```

```json
{
  "name": "pm_runtime_barrier",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586300480,
      "name": "pm_runtime_barrier",
      "external": true,
      "loc": "drivers/base/power/runtime.c:1294",
      "file": "drivers/base/power/runtime.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci.c:pci_config_pm_runtime_get",
        "drivers/base/core.c:device_shutdown",
        "drivers/base/dd.c:driver_probe_device",
        "drivers/base/power/main.c:__device_suspend",
        "drivers/usb/core/hub.c:hub_event",
        "drivers/usb/core/hub.c:usb_disconnect",
        "drivers/usb/core/hub.c:hub_post_reset",
        "drivers/usb/core/hub.c:hub_pre_reset"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586300480,
      "name": "pm_runtime_barrier",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 136
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
