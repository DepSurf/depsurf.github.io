# Function: <code>acpi_os_remove_interrupt_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583539237,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:864",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583539237,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583860188,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:586",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583860188,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583999264,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:581",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583999264,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584049731,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:580",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584046880,
      "name": "acpi_os_remove_interrupt_handler.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584047840,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584316051,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:580",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311392,
      "name": "acpi_os_remove_interrupt_handler.part.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    },
    {
      "addr": 18446744071584311872,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584532016,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:585",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584532016,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584629344,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:585",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584629344,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584829024,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:571",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584829024,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584964752,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:591",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584964752,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585664355,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:591",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585660304,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585790035,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:595",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585785920,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585670387,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:596",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585666288,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586149987,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:596",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586145760,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587382771,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:595",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587378160,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588633235,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:595",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588627952,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588920979,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:595",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588915712,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589217251,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:592",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ],
      "caller_func": [
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589211776,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497379640,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:591",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497379640,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584914928,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:591",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584914928,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584820848,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:591",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584820848,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584916336,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:591",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584916336,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```

```json
{
  "name": "acpi_os_remove_interrupt_handler",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585022416,
      "name": "acpi_os_remove_interrupt_handler",
      "external": true,
      "loc": "drivers/acpi/osl.c:591",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_terminate",
        "drivers/acpi/acpica/evgpeutil.c:acpi_ev_delete_gpe_xrupt",
        "drivers/acpi/acpica/evsci.c:acpi_ev_remove_all_sci_handlers"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585022416,
      "name": "acpi_os_remove_interrupt_handler",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
acpi_status acpi_os_remove_interrupt_handler(u32 gsi, acpi_osd_handler handler)
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
