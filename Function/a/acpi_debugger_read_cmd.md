# Function: <code>acpi_debugger_read_cmd</code>

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
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": false,
      "loc": "include/linux/acpi.h:177",
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
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584313888,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:926",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584313888,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584533904,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:931",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584533904,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584631232,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:936",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584631232,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584830928,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:922",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584830928,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584966656,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:942",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584966656,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585662240,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:942",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585662240,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585787920,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:946",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585787920,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585668336,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:947",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585668336,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:947",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592406452,
      "name": "acpi_debugger_read_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586147840,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:949",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594272037,
      "name": "acpi_debugger_read_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071587380432,
      "name": "acpi_debugger_read_cmd",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:949",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596218179,
      "name": "acpi_debugger_read_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588630560,
      "name": "acpi_debugger_read_cmd",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:949",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596744886,
      "name": "acpi_debugger_read_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071588918304,
      "name": "acpi_debugger_read_cmd",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:946",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597653434,
      "name": "acpi_debugger_read_cmd.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071589214480,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 199
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
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": false,
      "loc": "include/linux/acpi.h:195",
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
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": false,
      "loc": "include/linux/acpi.h:195",
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
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_debugger_read_cmd",
      "external": false,
      "loc": "include/linux/acpi.h:195",
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584918240,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:942",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584918240,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```

```json
{
  "name": "acpi_debugger_read_cmd",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585024384,
      "name": "acpi_debugger_read_cmd",
      "external": true,
      "loc": "drivers/acpi/osl.c:942",
      "file": "drivers/acpi/osl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/osl.c:acpi_os_get_line"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585024384,
      "name": "acpi_debugger_read_cmd",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
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
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
ssize_t acpi_debugger_read_cmd(char * buffer, size_t buffer_length)
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
