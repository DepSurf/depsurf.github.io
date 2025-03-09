# Function: <code>acpi_dev_needs_resume</code>

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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584331568,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:946",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584331568,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584552304,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:946",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584552304,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584650032,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:947",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584650032,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584849440,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:991",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584849440,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584985184,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:996",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584985184,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585683008,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:996",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585683008,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585805296,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:992",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585805296,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585686000,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:991",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585686000,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586166016,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:991",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586166016,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587400128,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:1017",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587400128,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588653728,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:1079",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588653728,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588941680,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:1079",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588941680,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589238304,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:1092",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238304,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497394184,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:996",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497394184,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584929840,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:996",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584929840,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584838576,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:996",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584838576,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584936768,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:996",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584936768,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_needs_resume",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585042944,
      "name": "acpi_dev_needs_resume",
      "external": false,
      "loc": "drivers/acpi/device_pm.c:996",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_subsys_poweroff",
        "drivers/acpi/device_pm.c:acpi_subsys_suspend",
        "drivers/acpi/device_pm.c:acpi_subsys_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042944,
      "name": "acpi_dev_needs_resume",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 230
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
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
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
bool acpi_dev_needs_resume(struct device * dev, struct acpi_device * adev)
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
