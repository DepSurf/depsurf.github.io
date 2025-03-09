# Function: <code>efi_reboot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585997056,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:10",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585997056,
      "name": "efi_reboot",
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586402464,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:10",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586402464,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586611744,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:10",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586611744,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586736896,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:10",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586736896,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 197
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587221376,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587221376,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 203
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587522637,
      "name": "efi_reboot.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587522432,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587703469,
      "name": "efi_reboot.cold.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
    },
    {
      "addr": 18446744071587703264,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 177
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587982477,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587982288,
      "name": "efi_reboot",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588189677,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588189488,
      "name": "efi_reboot",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589055005,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071589054816,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591606296,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071589063232,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591550138,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588950320,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 173
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589659456,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589659456,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 283
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591162272,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591162272,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 297
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592884608,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592884608,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 301
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593323216,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593323216,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594080256,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594080256,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 300
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501544992,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/process.c:machine_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501544992,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 244
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234059208,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3234059208,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 256
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
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587808109,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587807920,
      "name": "efi_reboot",
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
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587511533,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071587511344,
      "name": "efi_reboot",
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
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588144205,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588144016,
      "name": "efi_reboot",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```

```json
{
  "name": "efi_reboot",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "efi_reboot",
      "external": true,
      "loc": "drivers/firmware/efi/reboot.c:13",
      "file": "drivers/firmware/efi/reboot.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/reboot.c:native_machine_emergency_restart"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588261725,
      "name": "efi_reboot.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    },
    {
      "addr": 18446744071588261536,
      "name": "efi_reboot",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void efi_reboot(enum reboot_mode reboot_mode, const char * __unused)
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
