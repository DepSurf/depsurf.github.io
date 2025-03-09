# Function: <code>acpi_os_vprintf</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583538604,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:225",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_error",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583538604,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583859615,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:156",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583859615,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583998639,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:157",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583998639,
      "name": "acpi_os_vprintf",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584047200,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:156",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584047200,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584313632,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:156",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313632,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 131
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:158",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584536648,
      "name": "acpi_os_vprintf.cold.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071584533728,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584633864,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:158",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584633864,
      "name": "acpi_os_vprintf.cold.22",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071584631056,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584833651,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:144",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584833651,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584830752,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584969379,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:147",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584969379,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584966480,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585662189,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:147",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_printf"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585664808,
      "name": "acpi_os_vprintf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071585665131,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071585662032,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585787869,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:150",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_printf"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591430288,
      "name": "acpi_os_vprintf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071591430611,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071585787712,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585668274,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:153",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_printf"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591371644,
      "name": "acpi_os_vprintf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071591371976,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071585668112,
      "name": "acpi_os_vprintf",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586147778,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:153",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_printf"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592406026,
      "name": "acpi_os_vprintf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 18446744071592406420,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    },
    {
      "addr": 18446744071586147616,
      "name": "acpi_os_vprintf",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587380357,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:152",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/osl.c:acpi_os_printf"
      ],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594271596,
      "name": "acpi_os_vprintf.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    },
    {
      "addr": 18446744071594272017,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 10
    },
    {
      "addr": 18446744071587380192,
      "name": "acpi_os_vprintf",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588630224,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:152",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588630224,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588917968,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:152",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588917968,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589214144,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:152",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589214144,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void acpi_os_vprintf(const char * fmt, va_list args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497383404,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:147",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497383404,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584917341,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:147",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917341,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584823261,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:147",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584823261,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 102
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584920963,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:147",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584920963,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071584918064,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```

```json
{
  "name": "acpi_os_vprintf",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585027107,
      "name": "acpi_os_vprintf",
      "external": true,
      "loc": "drivers/acpi/osl.c:147",
      "file": "drivers/acpi/osl.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_printf",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print_raw",
        "drivers/acpi/acpica/utdebug.c:acpi_debug_print",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_bios_error",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_info",
        "drivers/acpi/acpica/uterror.c:acpi_ut_predefined_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_bios_error",
        "drivers/acpi/acpica/utxferror.c:acpi_info",
        "drivers/acpi/acpica/utxferror.c:acpi_warning",
        "drivers/acpi/acpica/utxferror.c:acpi_exception",
        "drivers/acpi/acpica/utxferror.c:acpi_error"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585027107,
      "name": "acpi_os_vprintf.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 18446744071585024208,
      "name": "acpi_os_vprintf",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 50
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
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag * args</code> ➡️ <code>va_list args</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_os_vprintf(const char * fmt, struct __va_list_tag * args)
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
