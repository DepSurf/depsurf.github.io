# Function: <code>efi_call_virt_check_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586415664,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:34",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_high_mono_count",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_next_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_variable",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_wakeup_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_set_time",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_get_time"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586415664,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586624960,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:36",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586624960,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586748928,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:36",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586748928,
      "name": "efi_call_virt_check_flags",
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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587233360,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:36",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587233360,
      "name": "efi_call_virt_check_flags",
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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:36",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587538101,
      "name": "efi_call_virt_check_flags.cold.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587534240,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:92",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587722130,
      "name": "efi_call_virt_check_flags.cold.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587718688,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 104
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588001826,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587997792,
      "name": "efi_call_virt_check_flags",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588209346,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588205312,
      "name": "efi_call_virt_check_flags",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589076370,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589072272,
      "name": "efi_call_virt_check_flags",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591611406,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589076000,
      "name": "efi_call_virt_check_flags",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591554620,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588962752,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592674337,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071589672288,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
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
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594559573,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071591176032,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592899696,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:106",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592899696,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593338240,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:106",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593338240,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 133
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
void efi_call_virt_check_flags(long unsigned int flags, const void * caller)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594093488,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:148",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594093488,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501560920,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501560920,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 160
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234069328,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234069328,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587823266,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587819232,
      "name": "efi_call_virt_check_flags",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587531090,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071587527152,
      "name": "efi_call_virt_check_flags",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588163874,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588159840,
      "name": "efi_call_virt_check_flags",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```

```json
{
  "name": "efi_call_virt_check_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_call_virt_check_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:104",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/firmware/efi/runtime-wrappers.c:virt_efi_reset_system",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588281698,
      "name": "efi_call_virt_check_flags.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071588277248,
      "name": "efi_call_virt_check_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 112
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```
</details>
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
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * caller</code>
</li>
<li>
<b>Param removed. </b>
<code>const char * call</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void efi_call_virt_check_flags(long unsigned int flags, const char * call)
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
