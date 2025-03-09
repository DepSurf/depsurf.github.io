# Function: <code>acpi_os_prepare_sleep</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583540964,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1880",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583540964,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583861938,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1685",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583861938,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584001014,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1680",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584001014,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584049998,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1679",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049856,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 54
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584316318,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1689",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316176,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584536369,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1764",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536224,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584633585,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1770",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633440,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584833361,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1756",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833200,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584969089,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1776",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968928,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585664705,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1778",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664560,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585790401,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1806",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585790256,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585670753,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1795",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670608,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586150353,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1790",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586150208,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587383163,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1707",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587382960,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588633707,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1707",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588633440,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588921451,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1707",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921184,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589217723,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1700",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589217456,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 87
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
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497383320,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1776",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497382856,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 124
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584917169,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1776",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917008,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584823089,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1776",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584822928,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584920673,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1776",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920512,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```

```json
{
  "name": "acpi_os_prepare_sleep",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585026817,
      "name": "acpi_os_prepare_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1776",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_enter_sleep"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585026656,
      "name": "acpi_os_prepare_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_os_prepare_sleep(u8 sleep_state, u32 pm1a_control, u32 pm1b_control)
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
