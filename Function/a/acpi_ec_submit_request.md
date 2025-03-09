# Function: <code>acpi_ec_submit_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583578405,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:367",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583900877,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:372",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583900877,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584041385,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:403",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584041385,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 46
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584099712,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:407",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584099712,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584371168,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:406",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584371168,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584592144,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:406",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584592144,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584689824,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:406",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584689824,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584890432,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:396",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584890432,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585026176,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:398",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585026176,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585728149,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:396",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585850293,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:379",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585728789,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:380",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586210690,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:381",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587448046,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:377",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588708640,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:378",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588708640,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588996864,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:378",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588996864,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589301120,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:378",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589301120,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497434872,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:398",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584968560,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:398",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584968560,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584877360,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:398",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584877360,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584977760,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:398",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584977760,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_submit_request",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585083936,
      "name": "acpi_ec_submit_request",
      "external": false,
      "loc": "drivers/acpi/ec.c:398",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_start",
        "drivers/acpi/ec.c:acpi_ec_transaction"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585083936,
      "name": "acpi_ec_submit_request",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 163
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
void acpi_ec_submit_request(struct acpi_ec * ec)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void acpi_ec_submit_request(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void acpi_ec_submit_request(struct acpi_ec * ec)
```
</details>
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
void acpi_ec_submit_request(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void acpi_ec_submit_request(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void acpi_ec_submit_request(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void acpi_ec_submit_request(struct acpi_ec * ec)
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
