# Function: <code>__acpi_device_wakeup_enable</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584332000,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:704",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584332000,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584552736,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:704",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552736,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584650480,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:705",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584650480,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 155
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849904,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:746",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849904,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584985648,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:751",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985648,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585683376,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:751",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683376,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805664,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:751",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805664,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585686368,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:748",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585686368,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166384,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:748",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166384,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 306
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587400528,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:774",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400528,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588654160,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:836",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588654160,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588942112,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:836",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588942112,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589238736,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:849",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238736,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 285
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
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497397504,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:751",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497397504,
      "name": "__acpi_device_wakeup_enable.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 176
    }
  ]
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584930304,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:751",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930304,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584839040,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:751",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584839040,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584937232,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:751",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584937232,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```

```json
{
  "name": "__acpi_device_wakeup_enable",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585043408,
      "name": "__acpi_device_wakeup_enable",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:751",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_suspend",
        "drivers/acpi/device_pm.c:__acpi_pm_set_device_wakeup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585043408,
      "name": "__acpi_device_wakeup_enable",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 215
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```
</details>
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
<b>Param removed. </b>
<code>int max_count</code>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __acpi_device_wakeup_enable(struct acpi_device * adev, u32 target_state, int max_count)
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
