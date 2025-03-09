# Function: <code>__battery_hook_unregister</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:673",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584938288,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071584942029,
      "name": "__battery_hook_unregister.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585046017,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:686",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042192,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071585046017,
      "name": "__battery_hook_unregister.cold.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585250026,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:673",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585245648,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071585250026,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585387917,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:696",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585383424,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071585387917,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:696",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_register",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586091216,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071586096946,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:685",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_register",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212016,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071591440787,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:691",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_register",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586086608,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071591381900,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:694",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_register",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586583824,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071592418813,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:689",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_register",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844080,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071594286506,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589186688,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:689",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_exit",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_register",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589186688,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589480768,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:700",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_exit",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_register",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589480768,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589787520,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:700",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_exit",
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_register",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589787520,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 329
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497656864,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:696",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497656864,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585338317,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:696",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585333824,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071585338317,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```

```json
{
  "name": "__battery_hook_unregister",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585445645,
      "name": "__battery_hook_unregister",
      "external": false,
      "loc": "drivers/acpi/battery.c:696",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:sysfs_add_battery",
        "drivers/acpi/battery.c:battery_hook_exit",
        "drivers/acpi/battery.c:battery_hook_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585441152,
      "name": "__battery_hook_unregister",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 161
    },
    {
      "addr": 18446744071585445645,
      "name": "__battery_hook_unregister.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```
</details>
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
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void __battery_hook_unregister(struct acpi_battery_hook * hook, int lock)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
