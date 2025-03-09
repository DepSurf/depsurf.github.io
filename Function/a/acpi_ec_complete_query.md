# Function: <code>acpi_ec_complete_query</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583576277,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:433",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_event_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576277,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583898594,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:440",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583898594,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584038518,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:472",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038518,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099632,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:478",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099632,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584371088,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:477",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371088,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584593968,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:477",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584593968,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689744,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:477",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689744,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890352,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:467",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890352,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585026096,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:469",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585026096,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585727936,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:475",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585727936,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585850080,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:458",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585850080,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585728576,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:459",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585728576,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586210480,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:461",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586210480,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497432952,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:469",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497432952,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 172
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584968480,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:469",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968480,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877280,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:469",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877280,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584977680,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:469",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584977680,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_complete_query",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083856,
      "name": "acpi_ec_complete_query",
      "external": false,
      "loc": "drivers/acpi/ec.c:469",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_event_handler",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:advance_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083856,
      "name": "acpi_ec_complete_query",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void acpi_ec_complete_query(struct acpi_ec * ec)
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
void acpi_ec_complete_query(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ec_complete_query(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ec_complete_query(struct acpi_ec * ec)
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
