# Function: <code>acpi_target_system_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583544976,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:90",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583544976,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583866008,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:113",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583866008,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584005084,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:96",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_wake",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584005084,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584055152,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:96",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare",
        "drivers/acpi/device_pm.c:acpi_dev_suspend_late",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584055152,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584322336,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:96",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584322336,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584543024,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:96",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584543024,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640240,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:96",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640240,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584840112,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:94",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584840112,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584975840,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:98",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584975840,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672304,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:101",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672304,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585796816,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:97",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585796816,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585677504,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:97",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585677504,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586157168,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:98",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586157168,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587390720,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:97",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587390720,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588642560,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:101",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588642560,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588930496,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:101",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588930496,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589227104,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:101",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589227104,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_target_system_state",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:663",
      "file": "drivers/pci/pci-acpi.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 0,
      "name": "acpi_target_system_state",
      "external": false,
      "loc": "include/acpi/acpi_bus.h:663",
      "file": "drivers/acpi/device_pm.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584923408,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:98",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923408,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584829280,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:98",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584829280,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584927424,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:98",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584927424,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
u32 acpi_target_system_state()
```

```json
{
  "name": "acpi_target_system_state",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585033568,
      "name": "acpi_target_system_state",
      "external": true,
      "loc": "drivers/acpi/sleep.c:98",
      "file": "drivers/acpi/sleep.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/pci/pci-acpi.c:acpi_pci_need_resume",
        "drivers/acpi/device_pm.c:acpi_dev_needs_resume",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup",
        "drivers/acpi/device_pm.c:acpi_pm_device_sleep_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585033568,
      "name": "acpi_target_system_state",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 17
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
u32 acpi_target_system_state()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
u32 acpi_target_system_state()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
u32 acpi_target_system_state()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
u32 acpi_target_system_state()
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
