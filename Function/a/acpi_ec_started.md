# Function: <code>acpi_ec_started</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583579108,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:231",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:acpi_ec_stop"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583903719,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:236",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
bool acpi_ec_started(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584037057,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:243",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584037057,
      "name": "acpi_ec_started",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 38
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584097277,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:247",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584368749,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:246",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584590013,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:246",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584687421,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:246",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584887885,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:236",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585023629,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:238",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585725468,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:236",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:acpi_ec_enable_event",
        "drivers/acpi/ec.c:acpi_ec_submit_query"
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585847532,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:236",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:acpi_ec_enable_event",
        "drivers/acpi/ec.c:acpi_ec_submit_query"
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585726044,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:237",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586207740,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:238",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587443965,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:234",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
bool acpi_ec_started(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701648,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:235",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701648,
      "name": "acpi_ec_started",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
bool acpi_ec_started(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588989792,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:235",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588989792,
      "name": "acpi_ec_started",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
bool acpi_ec_started(struct acpi_ec * ec)
```

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589293952,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:235",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction_unlocked",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589293952,
      "name": "acpi_ec_started",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497435112,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:238",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584966013,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:238",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584874813,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:238",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584975213,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:238",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ec_started",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585081389,
      "name": "acpi_ec_started",
      "external": false,
      "loc": "drivers/acpi/ec.c:238",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_stop",
        "drivers/acpi/ec.c:acpi_ec_transaction",
        "drivers/acpi/ec.c:advance_transaction",
        "drivers/acpi/ec.c:acpi_ec_enable_event"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
bool acpi_ec_started(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
bool acpi_ec_started(struct acpi_ec * ec)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
bool acpi_ec_started(struct acpi_ec * ec)
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
