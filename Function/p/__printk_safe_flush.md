# Function: <code>__printk_safe_flush</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579782032,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:192",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579782032,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579815472,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:189",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579815472,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 502
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:192",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579849232,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 353
    },
    {
      "addr": 18446744071579850197,
      "name": "__printk_safe_flush.cold.6",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:192",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579896256,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 337
    },
    {
      "addr": 18446744071579897212,
      "name": "__printk_safe_flush.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579931056,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071579931932,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579981200,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071579982060,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:181",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580028656,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071580029776,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:183",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580007248,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    },
    {
      "addr": 18446744071591302366,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 39
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:183",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580008256,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    },
    {
      "addr": 18446744071591245044,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
    }
  ]
}
```
</details>
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491166008,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491166008,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 708
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225192648,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225192648,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 580
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284064960,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284064960,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 696
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271719486,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271719486,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579949936,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071579950796,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579887824,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071579888684,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579941472,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071579942332,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __printk_safe_flush(struct irq_work * work)
```

```json
{
  "name": "__printk_safe_flush",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__printk_safe_flush",
      "external": false,
      "loc": "kernel/printk/printk_safe.c:180",
      "file": "kernel/printk/printk_safe.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/printk/printk_safe.c:printk_safe_flush",
        "kernel/printk/printk_safe.c:printk_safe_flush"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579987824,
      "name": "__printk_safe_flush",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 292
    },
    {
      "addr": 18446744071579988718,
      "name": "__printk_safe_flush.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
void __printk_safe_flush(struct irq_work * work)
```
</details>
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void __printk_safe_flush(struct irq_work * work)
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
