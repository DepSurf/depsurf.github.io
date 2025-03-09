# Function: <code>insn_jump_into_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579238605,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:202",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
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
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579238093,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:203",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579250541,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:203",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579246518,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:215",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579262784,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:215",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579262784,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579273984,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:215",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579273984,
      "name": "insn_jump_into_range",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579297984,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:220",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579297984,
      "name": "insn_jump_into_range",
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579314480,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:206",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314480,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579318560,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:206",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579318560,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579347744,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:227",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347744,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579347120,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:229",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579347120,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579351728,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:229",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579351728,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579409440,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:229",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579409440,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579475504,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:236",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579475504,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
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
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579568064,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:237",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579568064,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 121
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579581381,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:237",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
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
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579611173,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:237",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579314464,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:206",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314464,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579249056,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:206",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249056,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579314384,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:206",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579314384,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```

```json
{
  "name": "insn_jump_into_range",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579322656,
      "name": "insn_jump_into_range",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/opt.c:206",
      "file": "arch/x86/kernel/kprobes/opt.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/kprobes/opt.c:can_optimize"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579322656,
      "name": "insn_jump_into_range",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 113
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int insn_jump_into_range(struct insn * insn, long unsigned int start, int len)
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
