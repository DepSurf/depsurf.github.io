# Function: <code>__copy_instruction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __copy_instruction(u8 * dest, u8 * src)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579237200,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:353",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579237200,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 456
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
int __copy_instruction(u8 * dest, u8 * src)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579236688,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:355",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579236688,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
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
int __copy_instruction(u8 * dest, u8 * src)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249136,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:356",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe",
        "arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249136,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 449
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579244816,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:352",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579244816,
      "name": "__copy_instruction",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579261280,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:353",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579261280,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 279
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 0,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:353",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273616,
      "name": "__copy_instruction.cold.18",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579272384,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579296643,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:351",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297619,
      "name": "__copy_instruction.cold.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579296544,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579313107,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:338",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314213,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579313008,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579317251,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:338",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318287,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579317152,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579346144,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:339",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579344048,
      "name": "__copy_instruction.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071579347209,
      "name": "__copy_instruction.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579346144,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579345504,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:340",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579343040,
      "name": "__copy_instruction.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 211
    },
    {
      "addr": 18446744071591263096,
      "name": "__copy_instruction.part.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579345504,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 162
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579350101,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:311",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591205700,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579350000,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 289
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579407845,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:311",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592077796,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071579407744,
      "name": "__copy_instruction",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:321",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593844247,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579474192,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 326
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
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579566624,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:323",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579566624,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579578944,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:323",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579578944,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579608736,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:357",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579608736,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 364
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579313155,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:338",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314191,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579313056,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579247747,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:338",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579248783,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579247648,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579313075,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:338",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314111,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579312976,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```

```json
{
  "name": "__copy_instruction",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579321347,
      "name": "__copy_instruction",
      "external": true,
      "loc": "arch/x86/kernel/kprobes/core.c:338",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/core.c:arch_copy_kprobe",
        "arch/x86/kernel/kprobes/opt.c:copy_optimized_instructions"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322383,
      "name": "__copy_instruction.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    },
    {
      "addr": 18446744071579321248,
      "name": "__copy_instruction",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 275
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
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct insn * insn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * real</code>
</li>
<li>
<b>Param reordered. </b>
<code>dest, src, insn</code> ➡️ <code>dest, src, real, insn</code>
</li>
</ul>
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __copy_instruction(u8 * dest, u8 * src, u8 * real, struct insn * insn)
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
