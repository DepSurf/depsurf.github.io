# Function: <code>extract_package</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583767232,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:392",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583767232,
      "name": "extract_package",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584093150,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:392",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584093150,
      "name": "extract_package",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584235771,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:392",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584235771,
      "name": "extract_package",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584311628,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:398",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584311232,
      "name": "extract_package.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584710876,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:402",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584710480,
      "name": "extract_package.part.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 216
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584937212,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:421",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584936832,
      "name": "extract_package.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585041116,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:435",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585040736,
      "name": "extract_package.part.10",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 206
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585245180,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:422",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585244784,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585382956,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:445",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585382560,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586092844,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:445",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586092464,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586213647,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:434",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586213264,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586088207,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:427",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586087824,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586585423,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:430",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586585040,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 205
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
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587844768,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:425",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587844768,
      "name": "extract_package",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589187680,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:425",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589187680,
      "name": "extract_package",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589481760,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:427",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589481760,
      "name": "extract_package",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589788512,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:427",
      "file": "drivers/acpi/battery.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589788512,
      "name": "extract_package",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497655784,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:445",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497655344,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585333356,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:445",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585332960,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "extract_package",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585440684,
      "name": "extract_package",
      "external": false,
      "loc": "drivers/acpi/battery.c:445",
      "file": "drivers/acpi/battery.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ],
      "caller_func": [
        "drivers/acpi/battery.c:acpi_battery_get_state",
        "drivers/acpi/battery.c:acpi_battery_get_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585440288,
      "name": "extract_package.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
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
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int extract_package(struct acpi_battery * battery, union acpi_object * package, const struct acpi_offsets * offsets, int num)
```
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
