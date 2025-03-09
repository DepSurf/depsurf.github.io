# Function: <code>acpi_dev_resume</code>

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
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584335280,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:903",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584335280,
      "name": "acpi_dev_resume",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584556112,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:903",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584556112,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584653872,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:904",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584653872,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584853264,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:948",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584853264,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584989152,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:953",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584989152,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585686576,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:953",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585686576,
      "name": "acpi_dev_resume",
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
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585808864,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:949",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585808864,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585688512,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:946",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585688512,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586168736,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:946",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586168736,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587403440,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:972",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587403440,
      "name": "acpi_dev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588657696,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1034",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588657696,
      "name": "acpi_dev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588945664,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1034",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588945664,
      "name": "acpi_dev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589242288,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:1047",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589242288,
      "name": "acpi_dev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 153
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
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497399224,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:953",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497399224,
      "name": "acpi_dev_resume",
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
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584933552,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:953",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584933552,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584842352,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:953",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584842352,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584940736,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:953",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584940736,
      "name": "acpi_dev_resume",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int acpi_dev_resume(struct device * dev)
```

```json
{
  "name": "acpi_dev_resume",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585046912,
      "name": "acpi_dev_resume",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:953",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_restore_early",
        "drivers/acpi/device_pm.c:acpi_subsys_resume_early",
        "drivers/acpi/device_pm.c:acpi_subsys_runtime_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_resume",
        "drivers/acpi/acpi_lpss.c:acpi_lpss_activate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585046912,
      "name": "acpi_dev_resume",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
int acpi_dev_resume(struct device * dev)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_dev_resume(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_dev_resume(struct device * dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_dev_resume(struct device * dev)
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
