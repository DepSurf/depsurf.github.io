# Function: <code>cont_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579725712,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1569",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579725712,
      "name": "cont_flush.part.14",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579750891,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1646",
      "file": "kernel/printk/printk.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit",
        "kernel/printk/printk.c:vprintk_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579746016,
      "name": "cont_flush.part.17",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 167
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579774160,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1593",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579774160,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579770256,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1620",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579770256,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803280,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1608",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_emit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803280,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836704,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1752",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836704,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579883424,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1771",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579883424,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579918832,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1821",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579918832,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579968896,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579968896,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580016032,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1856",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580016032,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491149056,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491149056,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225179168,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225179168,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284047712,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284047712,
      "name": "cont_flush",
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
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271706848,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271706848,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579937632,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579937632,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579876112,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579876112,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579929168,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579929168,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
void cont_flush()
```

```json
{
  "name": "cont_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579975152,
      "name": "cont_flush",
      "external": false,
      "loc": "kernel/printk/printk.c:1831",
      "file": "kernel/printk/printk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk.c:vprintk_store",
        "kernel/printk/printk.c:cont_add",
        "kernel/printk/printk.c:cont_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579975152,
      "name": "cont_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
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
<summary>Added between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➕</summary>

```c
void cont_flush()
```
</details>
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
<details>
<summary>Removed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➖</summary>

```c
void cont_flush()
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
