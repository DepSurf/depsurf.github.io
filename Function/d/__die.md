# Function: <code>__die</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049088,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:254",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:pgtable_bad",
        "arch/x86/mm/fault.c:no_context"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579049088,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 210
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579045728,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:275",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579045728,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579044128,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:244",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044128,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 190
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579036656,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:246",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579036656,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 183
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579044544,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:306",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579044544,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 218
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579050805,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:377",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050805,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579055610,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:368",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579055610,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 206
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579063338,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:368",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579063338,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579065434,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:368",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065434,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579073734,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:411",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579073734,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591245963,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:428",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591245963,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591189757,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:428",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:page_fault_oops",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591189757,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592053319,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:428",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:page_fault_oops",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592053319,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 51
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593820124,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:422",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:page_fault_oops",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593820124,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579180506,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:428",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:die"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579180320,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579183898,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:431",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:die"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579183712,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579213114,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:431",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/dumpstack.c:die"
      ],
      "caller_func": [
        "arch/x86/mm/fault.c:page_fault_oops",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579212928,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 118
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
  "name": "__die",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490240416,
      "name": "__die",
      "external": false,
      "loc": "arch/arm64/kernel/traps.c:151",
      "file": "arch/arm64/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm64/kernel/traps.c:die"
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "__die",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224433588,
      "name": "__die",
      "external": false,
      "loc": "arch/arm/kernel/traps.c:265",
      "file": "arch/arm/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/traps.c:die"
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055282357096,
      "name": "__die",
      "external": false,
      "loc": "arch/powerpc/kernel/traps.c:262",
      "file": "arch/powerpc/kernel/traps.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/powerpc/kernel/traps.c:die"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055282357096,
      "name": "__die",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 348
    }
  ]
}
```
</details>
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579065786,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:368",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065786,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578998538,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:368",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578998538,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579065370,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:368",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579065370,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __die(const char * str, struct pt_regs * regs, long int err)
```

```json
{
  "name": "__die",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579069434,
      "name": "__die",
      "external": true,
      "loc": "arch/x86/kernel/dumpstack.c:368",
      "file": "arch/x86/kernel/dumpstack.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/dumpstack.c:die",
        "arch/x86/mm/fault.c:no_context",
        "arch/x86/mm/fault.c:pgtable_bad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579069434,
      "name": "__die",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 217
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
int __die(const char * str, struct pt_regs * regs, long int err)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int __die(const char * str, struct pt_regs * regs, long int err)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int __die(const char * str, struct pt_regs * regs, long int err)
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
