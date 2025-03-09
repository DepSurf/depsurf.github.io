# Function: <code>acpi_debugger_create_thread</code>

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
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": false,
      "loc": "include/linux/acpi.h:166",
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
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": false,
      "loc": "include/linux/acpi.h:189",
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
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": false,
      "loc": "include/linux/acpi.h:194",
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584312928,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:866",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584312928,
      "name": "acpi_debugger_create_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533088,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:871",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533088,
      "name": "acpi_debugger_create_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584630416,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:876",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584630416,
      "name": "acpi_debugger_create_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830112,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:862",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830112,
      "name": "acpi_debugger_create_thread",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584965840,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:882",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584965840,
      "name": "acpi_debugger_create_thread",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585661392,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:882",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585661392,
      "name": "acpi_debugger_create_thread",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585787072,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:886",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585787072,
      "name": "acpi_debugger_create_thread",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585667440,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:887",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585667440,
      "name": "acpi_debugger_create_thread",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:887",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592406311,
      "name": "acpi_debugger_create_thread.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586146912,
      "name": "acpi_debugger_create_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:889",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594271916,
      "name": "acpi_debugger_create_thread.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587379504,
      "name": "acpi_debugger_create_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:889",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596218139,
      "name": "acpi_debugger_create_thread.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588629440,
      "name": "acpi_debugger_create_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:889",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596744846,
      "name": "acpi_debugger_create_thread.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588917184,
      "name": "acpi_debugger_create_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:886",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597653394,
      "name": "acpi_debugger_create_thread.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589213248,
      "name": "acpi_debugger_create_thread",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": false,
      "loc": "include/linux/acpi.h:184",
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
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": false,
      "loc": "include/linux/acpi.h:184",
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
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_create_thread",
      "external": false,
      "loc": "include/linux/acpi.h:184",
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584917424,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:882",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584917424,
      "name": "acpi_debugger_create_thread",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```

```json
{
  "name": "acpi_debugger_create_thread",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585023568,
      "name": "acpi_debugger_create_thread",
      "external": true,
      "loc": "drivers/acpi/osl.c:882",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_execute"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585023568,
      "name": "acpi_debugger_create_thread",
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
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
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
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int acpi_debugger_create_thread(acpi_osd_exec_callback function, void * context)
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
