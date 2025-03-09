# Function: <code>__acpi_ec_flush_work</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585020208,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:529",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_flush_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585020208,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585732802,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:535",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend"
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
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585854951,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:518",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend"
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
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585733623,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:519",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend"
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
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586215616,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:521",
      "file": "drivers/acpi/ec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587441840,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:540",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587441840,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588701712,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:541",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588701712,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588989856,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:541",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588989856,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589294016,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:541",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_dispatch_gpe",
        "drivers/acpi/ec.c:acpi_ec_suspend"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589294016,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336497429976,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:529",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_flush_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336497429976,
      "name": "__acpi_ec_flush_work",
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
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584962592,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:529",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_flush_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584962592,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584871392,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:529",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_flush_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584871392,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584971792,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:529",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_flush_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584971792,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
void __acpi_ec_flush_work()
```

```json
{
  "name": "__acpi_ec_flush_work",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585077968,
      "name": "__acpi_ec_flush_work",
      "external": false,
      "loc": "drivers/acpi/ec.c:529",
      "file": "drivers/acpi/ec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/ec.c:acpi_ec_suspend",
        "drivers/acpi/ec.c:acpi_ec_flush_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585077968,
      "name": "__acpi_ec_flush_work",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 35
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
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void __acpi_ec_flush_work()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void __acpi_ec_flush_work()
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void __acpi_ec_flush_work()
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void __acpi_ec_flush_work()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void __acpi_ec_flush_work()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __acpi_ec_flush_work()
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
