# Function: <code>optimize_nops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579066303,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:339",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
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
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579062703,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:340",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
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
void optimize_nops(struct alt_instr * a, u8 * instr)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579061456,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:344",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579061456,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 195
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
void optimize_nops(struct alt_instr * a, u8 * instr)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579053312,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:344",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579053312,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
void optimize_nops(struct alt_instr * a, u8 * instr)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579062352,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:333",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579062352,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 223
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:333",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579066832,
      "name": "optimize_nops.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071579069970,
      "name": "optimize_nops.isra.5.cold.7",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:337",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579071424,
      "name": "optimize_nops.isra.5",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 147
    },
    {
      "addr": 18446744071579074594,
      "name": "optimize_nops.isra.5.cold.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:341",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579080304,
      "name": "optimize_nops.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071579084088,
      "name": "optimize_nops.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:341",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082304,
      "name": "optimize_nops.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071579086104,
      "name": "optimize_nops.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void optimize_nops(struct alt_instr * a, u8 * instr)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:341",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579093680,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071579097500,
      "name": "optimize_nops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void optimize_nops(struct alt_instr * a, u8 * instr)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:344",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579094896,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 140
    },
    {
      "addr": 18446744071591247554,
      "name": "optimize_nops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
void optimize_nops(struct alt_instr * a, u8 * instr)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:224",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579102960,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071591191446,
      "name": "optimize_nops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void optimize_nops(struct alt_instr * a, u8 * instr)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:224",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579126928,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 367
    },
    {
      "addr": 18446744071592055750,
      "name": "optimize_nops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void optimize_nops(u8 * instr, size_t len)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:228",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_retpolines",
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579158848,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 632
    },
    {
      "addr": 18446744071593822646,
      "name": "optimize_nops.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
void optimize_nops(u8 * instr, size_t len)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579208880,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:229",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_retpolines",
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579208880,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 782
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
void optimize_nops(u8 * instr, size_t len)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579213744,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:242",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_retpolines",
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579213744,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
void optimize_nops(u8 * instr, size_t len)
```

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579242784,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:242",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_retpolines",
        "arch/x86/kernel/alternative.c:optimize_nops_inplace"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579242784,
      "name": "optimize_nops",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:341",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082656,
      "name": "optimize_nops.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071579086456,
      "name": "optimize_nops.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:341",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579015312,
      "name": "optimize_nops.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    },
    {
      "addr": 18446744071579018888,
      "name": "optimize_nops.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:341",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579082240,
      "name": "optimize_nops.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071579086040,
      "name": "optimize_nops.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "optimize_nops",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "optimize_nops",
      "external": false,
      "loc": "arch/x86/kernel/alternative.c:341",
      "file": "arch/x86/kernel/alternative.c",
      "inline": "not declared, not inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/alternative.c:apply_alternatives"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579086336,
      "name": "optimize_nops.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 144
    },
    {
      "addr": 18446744071579090136,
      "name": "optimize_nops.isra.0.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
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
void optimize_nops(struct alt_instr * a, u8 * instr)
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
<details>
<summary>Removed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➖</summary>

```c
void optimize_nops(struct alt_instr * a, u8 * instr)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void optimize_nops(struct alt_instr * a, u8 * instr)
```
</details>
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>struct alt_instr * a</code>
</li>
<li>
<b>Param reordered. </b>
<code>a, instr</code> ➡️ <code>instr, len</code>
</li>
</ul>
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
