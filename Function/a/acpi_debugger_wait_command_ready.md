# Function: <code>acpi_debugger_wait_command_ready</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": false,
      "loc": "include/linux/acpi.h:182",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": false,
      "loc": "include/linux/acpi.h:205",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": false,
      "loc": "include/linux/acpi.h:210",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584314128,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:956",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584314128,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584534144,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:961",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584534144,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631472,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:966",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631472,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584831168,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:952",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584831168,
      "name": "acpi_debugger_wait_command_ready",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584966896,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:972",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584966896,
      "name": "acpi_debugger_wait_command_ready",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585662496,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:972",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662496,
      "name": "acpi_debugger_wait_command_ready",
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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585788176,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:976",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585788176,
      "name": "acpi_debugger_wait_command_ready",
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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668592,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:977",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668592,
      "name": "acpi_debugger_wait_command_ready",
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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:977",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592406472,
      "name": "acpi_debugger_wait_command_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586148096,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 198
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
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:979",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594272057,
      "name": "acpi_debugger_wait_command_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587380704,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:979",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596218199,
      "name": "acpi_debugger_wait_command_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588630864,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:979",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596744906,
      "name": "acpi_debugger_wait_command_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588918608,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:976",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597653454,
      "name": "acpi_debugger_wait_command_ready.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589214784,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": false,
      "loc": "include/linux/acpi.h:200",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": false,
      "loc": "include/linux/acpi.h:200",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_wait_command_ready",
      "external": false,
      "loc": "include/linux/acpi.h:200",
      "file": "drivers/acpi/osl.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584918480,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:972",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918480,
      "name": "acpi_debugger_wait_command_ready",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int acpi_debugger_wait_command_ready()
```

```json
{
  "name": "acpi_debugger_wait_command_ready",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585024624,
      "name": "acpi_debugger_wait_command_ready",
      "external": true,
      "loc": "drivers/acpi/osl.c:972",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_wait_command_ready"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585024624,
      "name": "acpi_debugger_wait_command_ready",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int acpi_debugger_wait_command_ready()
```
</details>
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
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int acpi_debugger_wait_command_ready()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_debugger_wait_command_ready()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_debugger_wait_command_ready()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_debugger_wait_command_ready()
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
int acpi_debugger_wait_command_ready()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int acpi_debugger_wait_command_ready()
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
