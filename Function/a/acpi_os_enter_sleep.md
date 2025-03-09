# Function: <code>acpi_os_enter_sleep</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584049984,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1729",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584049984,
      "name": "acpi_os_enter_sleep",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584316304,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1739",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584316304,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584536352,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1814",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536352,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584633568,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1820",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633568,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584833344,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1806",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833344,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584969072,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1826",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969072,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585664688,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1828",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664688,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585790384,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1856",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585790384,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585670736,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1845",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585670736,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586150336,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1840",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586150336,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587383136,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1757",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587383136,
      "name": "acpi_os_enter_sleep",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588633680,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1757",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588633680,
      "name": "acpi_os_enter_sleep",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588921424,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1757",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588921424,
      "name": "acpi_os_enter_sleep",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589217696,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1752",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589217696,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 96
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497383208,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1826",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497383208,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 168
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584917152,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1826",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917152,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584823072,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1826",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584823072,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584920656,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1826",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920656,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```

```json
{
  "name": "acpi_os_enter_sleep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585026800,
      "name": "acpi_os_enter_sleep",
      "external": true,
      "loc": "drivers/acpi/osl.c:1826",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/acpi/acpica/hwsleep.c:acpi_hw_legacy_sleep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585026800,
      "name": "acpi_os_enter_sleep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```
</details>
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
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_os_enter_sleep(u8 sleep_state, u32 reg_a_value, u32 reg_b_value)
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
