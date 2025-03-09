# Function: <code>strncat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strncat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582982336,
      "name": "strncat",
      "external": true,
      "loc": "lib/string.c:268",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582982336,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 70
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
char * strncat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583271520,
      "name": "strncat",
      "external": true,
      "loc": "lib/string.c:268",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583271520,
      "name": "strncat",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strncat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583390288,
      "name": "strncat",
      "external": true,
      "loc": "lib/string.c:268",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show",
        "drivers/tty/serial/serial_core.c:uart_proc_show"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583390288,
      "name": "strncat",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580200961,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:271",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/debug/kdb/kdb_main.c:kdb_main_loop"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588243952,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580251655,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:306",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588795376,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580311999,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:307",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589173552,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580364419,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:314",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589403472,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 62
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580417067,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:321",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589859504,
      "name": "strncat",
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580465819,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:342",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590085296,
      "name": "strncat",
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580550523,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:368",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083088,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580538427,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:409",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585232256,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580541611,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/fortify-string.h:150",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585115136,
      "name": "strncat",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580713041,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/fortify-string.h:150",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:event_hist_trigger_func",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585563808,
      "name": "strncat",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
char * strncat(const char * p, const const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580925090,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/fortify-string.h:224",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:last_cmd_set",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586719760,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
char * strncat(const char * p, const const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581217538,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/fortify-string.h:388",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:last_cmd_set",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595882272,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
char * strncat(const char * p, const const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581312052,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/fortify-string.h:458",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/trace/trace_events_hist.c:last_cmd_set",
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596399520,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
char * strncat(const char * p, const const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589679109,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/fortify-string.h:403",
      "file": "drivers/acpi/acpica/utnonansi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597294624,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336491741120,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:342",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/firmware/ti_sci.c:ti_sci_probe"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503863184,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225690244,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:342",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/serial_core.c:uart_line_info",
        "drivers/tty/serial/serial_core.c:uart_line_info",
        "drivers/tty/serial/serial_core.c:uart_line_info",
        "drivers/tty/serial/serial_core.c:uart_line_info",
        "drivers/tty/serial/serial_core.c:uart_line_info",
        "drivers/tty/serial/serial_core.c:uart_line_info"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3236490696,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055284773852,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:342",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/video/fbdev/offb.c:offb_init_fb"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297721568,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
char * strncat(char * dest, const char * src, size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936279761514,
      "name": "strncat",
      "external": true,
      "loc": "lib/string.c:305",
      "file": "lib/string.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279761514,
      "name": "strncat",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580434619,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:342",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589687552,
      "name": "strncat",
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580381691,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:342",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589413344,
      "name": "strncat",
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580425867,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:342",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590130928,
      "name": "strncat",
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
char * strncat(char * p, const char * q, __kernel_size_t count)
```

```json
{
  "name": "strncat",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580481451,
      "name": "strncat",
      "external": true,
      "loc": "include/linux/string.h:342",
      "file": "kernel/debug/kdb/kdb_main.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/utnonansi.c:acpi_ut_safe_strncat"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590181312,
      "name": "strncat",
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
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * p</code>
</li>
<li>
<b>Param added. </b>
<code>const char * q</code>
</li>
<li>
<b>Param removed. </b>
<code>char * dest</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * src</code>
</li>
<li>
<b>Param type changed. </b>
<code>size_t count</code> ➡️ <code>__kernel_size_t count</code>
</li>
</ul>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char * p</code> ➡️ <code>const char * p</code>
</li>
<li>
<b>Param type changed. </b>
<code>const char * q</code> ➡️ <code>const const char * q</code>
</li>
</ul>
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>char * dest</code>
</li>
<li>
<b>Param added. </b>
<code>const char * src</code>
</li>
<li>
<b>Param removed. </b>
<code>char * p</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * q</code>
</li>
<li>
<b>Param type changed. </b>
<code>__kernel_size_t count</code> ➡️ <code>size_t count</code>
</li>
</ul>
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
