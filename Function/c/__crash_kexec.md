# Function: <code>__crash_kexec</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579980656,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:881",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579980656,
      "name": "__crash_kexec.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071579980928,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580011152,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:883",
      "file": "kernel/kexec_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580011152,
      "name": "__crash_kexec.part.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 263
    },
    {
      "addr": 18446744071580011424,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 40
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580017632,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:917",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580017632,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580061264,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:927",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580061264,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 147
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580117296,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:931",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580117296,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 294
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580165296,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580165296,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580211408,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:936",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580211408,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580259808,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580259808,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580327520,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:944",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580327520,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580312992,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:943",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580312992,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580316480,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:944",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580316480,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580470192,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:945",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580470192,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580664048,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:965",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580664048,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580934336,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:954",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580934336,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581021056,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:1047",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581021056,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581119152,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:1035",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581119152,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 165
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491505800,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491505800,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 288
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225487608,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225487608,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 216
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284466400,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284466400,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 268
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "__crash_kexec",
      "external": false,
      "loc": "include/linux/kexec.h:396",
      "file": "kernel/panic.c",
      "inline": "declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580228608,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580228608,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580176096,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580176096,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580220080,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580220080,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
```

```json
{
  "name": "__crash_kexec",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580272912,
      "name": "__crash_kexec",
      "external": true,
      "loc": "kernel/kexec_core.c:938",
      "file": "kernel/kexec_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/panic.c:panic",
        "kernel/panic.c:panic",
        "kernel/kexec_core.c:crash_kexec"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580272912,
      "name": "__crash_kexec",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 286
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
void __crash_kexec(struct pt_regs * regs)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void __crash_kexec(struct pt_regs * regs)
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
