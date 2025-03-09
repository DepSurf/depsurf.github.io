# Function: <code>acpi_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583676122,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:127",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583676122,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 220
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583999837,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:126",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999837,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584141285,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:126",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584141285,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 229
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584207985,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:126",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584207985,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 228
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584538847,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:126",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584538847,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584763326,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584763326,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584864126,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584864126,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585067904,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585067904,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585204238,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585204238,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585909979,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585909979,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586031741,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586031741,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585908762,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585908762,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586396731,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586396731,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587645838,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587645838,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588948240,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588948240,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589238208,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589238208,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589544720,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589544720,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497542164,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497542164,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077118,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077118,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584992549,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584992549,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585155822,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585155822,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```

```json
{
  "name": "acpi_read",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585261982,
      "name": "acpi_read",
      "external": true,
      "loc": "drivers/acpi/acpica/hwxface.c:92",
      "file": "drivers/acpi/acpica/hwxface.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/hwesleep.c:acpi_hw_extended_sleep",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_cpufreq_target",
        "drivers/cpufreq/pcc-cpufreq.c:pcc_get_freq",
        "drivers/mailbox/pcc.c:pcc_send_data"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585261982,
      "name": "acpi_read",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_read(u64 * return_value, struct acpi_generic_address * reg)
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
