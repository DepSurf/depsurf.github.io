# Function: <code>acpi_sleep_prepare</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583546062,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:57",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_power_off_prepare"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583546062,
      "name": "acpi_sleep_prepare.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583546115,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583867546,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:80",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_suspend_begin_old",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583867114,
      "name": "acpi_sleep_prepare.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071583867629,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584006582,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:63",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_suspend_begin_old",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584006213,
      "name": "acpi_sleep_prepare.part.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    },
    {
      "addr": 18446744071584006665,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584056406,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:63",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584056224,
      "name": "acpi_sleep_prepare.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071584056288,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584326150,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:63",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584325920,
      "name": "acpi_sleep_prepare.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071584325984,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584546709,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:63",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584546480,
      "name": "acpi_sleep_prepare.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071584546544,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584643925,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:63",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584643696,
      "name": "acpi_sleep_prepare.part.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    },
    {
      "addr": 18446744071584643760,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584843157,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584842928,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071584842992,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584978949,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584978720,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071584978784,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585675813,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585675632,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585798421,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585798240,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585679573,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585679296,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586159493,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:63",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586159216,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594272956,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:63",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594272895,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588645125,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:67",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588643040,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588932997,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:67",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588931008,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589229605,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:67",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_suspend_begin_old"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589227616,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 99
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584924085,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584923920,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584830341,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830160,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071584830224,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584930533,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584930304,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071584930368,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int acpi_sleep_prepare(u32 acpi_state)
```

```json
{
  "name": "acpi_sleep_prepare",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585036677,
      "name": "acpi_sleep_prepare",
      "external": false,
      "loc": "drivers/acpi/sleep.c:61",
      "file": "drivers/acpi/sleep.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old"
      ],
      "caller_func": [
        "drivers/acpi/sleep.c:acpi_power_off_prepare",
        "drivers/acpi/sleep.c:acpi_hibernation_begin_old",
        "drivers/acpi/sleep.c:acpi_pm_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585036448,
      "name": "acpi_sleep_prepare.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    },
    {
      "addr": 18446744071585036512,
      "name": "acpi_sleep_prepare",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```
</details>
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
int acpi_sleep_prepare(u32 acpi_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_sleep_prepare(u32 acpi_state)
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
int acpi_sleep_prepare(u32 acpi_state)
```
</details>
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
