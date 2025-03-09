# Function: <code>acpi_ec_query</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583580536,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1063",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_clear",
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583580536,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 474
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583902691,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1070",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_clear"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583902691,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584043188,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1150",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584043188,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584101944,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1161",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584373400,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1163",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584596122,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1169",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584692058,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1181",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584892592,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1195",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584892592,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585028336,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1169",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585028336,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585729392,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1157",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585729392,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585851552,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1144",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585851552,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585730240,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1145",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585730240,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 527
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586212160,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1157",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586212160,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 545
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497440088,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1169",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497440088,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 492
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584970720,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1169",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584970720,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584879520,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1169",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584879520,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584979920,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1169",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584979920,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```

```json
{
  "name": "acpi_ec_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585086096,
      "name": "acpi_ec_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:1169",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585086096,
      "name": "acpi_ec_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 473
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```
</details>
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
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_ec_query(struct acpi_ec * ec, u8 * data)
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
