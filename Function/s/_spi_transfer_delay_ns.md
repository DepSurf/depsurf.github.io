# Function: <code>_spi_transfer_delay_ns</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586771440,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1093",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771440,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586917808,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586917808,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587743319,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1121",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec"
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
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587801194,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1145",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec"
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
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587680790,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1157",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec"
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
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588270769,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1231",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec"
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
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589652535,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1274",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591256062,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1389",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591613020,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1389",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_transfer_cs_change_delay_exec",
        "drivers/spi/spi.c:spi_transfer_cs_change_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592344668,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1462",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/spi/spi.c:spi_transfer_cs_change_delay_exec",
        "drivers/spi/spi.c:spi_transfer_cs_change_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec",
        "drivers/spi/spi.c:spi_delay_exec"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336499870464,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336499870464,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3232433560,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3232433560,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055293202016,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055293202016,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936276984376,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936276984376,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586674832,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586674832,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586543168,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586543168,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586872368,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586872368,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```

```json
{
  "name": "_spi_transfer_delay_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586978480,
      "name": "_spi_transfer_delay_ns",
      "external": false,
      "loc": "drivers/spi/spi.c:1094",
      "file": "drivers/spi/spi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:spi_transfer_one_message",
        "drivers/spi/spi.c:spi_transfer_one_message"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586978480,
      "name": "_spi_transfer_delay_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void _spi_transfer_delay_ns(u32 ns)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
