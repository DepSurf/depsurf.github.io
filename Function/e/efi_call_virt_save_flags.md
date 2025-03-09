# Function: <code>efi_call_virt_save_flags</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588000618,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587997760,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588208138,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588205280,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589075098,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589072240,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589078488,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589075968,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588964977,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588962720,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589674513,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589672256,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591176000,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591176000,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592899648,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:98",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592899648,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593338192,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:98",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/acpi/prmt.c:acpi_platformrt_space_handler",
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593338192,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594093440,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:140",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594093440,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 29
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501562572,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501560888,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234070704,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234069300,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587822058,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819200,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587529882,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587527136,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 13
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588162666,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588159808,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
long unsigned int efi_call_virt_save_flags()
```

```json
{
  "name": "efi_call_virt_save_flags",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588280433,
      "name": "efi_call_virt_save_flags",
      "external": true,
      "loc": "drivers/firmware/efi/runtime-wrappers.c:96",
      "file": "drivers/firmware/efi/runtime-wrappers.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_rts",
        "drivers/firmware/efi/runtime-wrappers.c:efi_call_virt_check_flags"
      ],
      "caller_func": [
        "arch/x86/platform/uv/bios_uv.c:__uv_bios_call"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588277216,
      "name": "efi_call_virt_save_flags",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 18
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
long unsigned int efi_call_virt_save_flags()
```
</details>
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int efi_call_virt_save_flags()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int efi_call_virt_save_flags()
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
