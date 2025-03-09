# Function: <code>acpi_watchdog_get_wdat</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584640016,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:61",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584640016,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584739120,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:61",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584739120,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 162
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:58",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584941168,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    },
    {
      "addr": 18446744071584941366,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585076960,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071585077158,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585781440,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585781440,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585902512,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585902512,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585779952,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585779952,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586264192,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    },
    {
      "addr": 18446744071592415021,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587507008,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071594282456,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588780816,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071596219956,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589070240,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071596746526,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589376032,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 208
    },
    {
      "addr": 18446744071597655174,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497481128,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497481128,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585006448,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071585006646,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584922096,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071584922294,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585028544,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071585028742,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```

```json
{
  "name": "acpi_watchdog_get_wdat",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_watchdog_get_wdat",
      "external": false,
      "loc": "drivers/acpi/acpi_watchdog.c:60",
      "file": "drivers/acpi/acpi_watchdog.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpi_watchdog.c:acpi_watchdog_init",
        "drivers/acpi/acpi_watchdog.c:acpi_has_watchdog"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585134704,
      "name": "acpi_watchdog_get_wdat",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 169
    },
    {
      "addr": 18446744071585134902,
      "name": "acpi_watchdog_get_wdat.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```
</details>
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
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
const struct acpi_table_wdat * acpi_watchdog_get_wdat()
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
