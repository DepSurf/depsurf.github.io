# Function: <code>fixup_bug</code>

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
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579027664,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:185",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_trap",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579027664,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579030583,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:173",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579029936,
      "name": "fixup_bug.part.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071579032128,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 24
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579035319,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:173",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579036160,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579039653,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:173",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579040736,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579047362,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:174",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579048368,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049602,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:174",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050608,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049954,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:174",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050960,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071578982882,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:174",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578983728,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579049538,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:174",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579050544,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```

```json
{
  "name": "fixup_bug",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579053330,
      "name": "fixup_bug",
      "external": true,
      "loc": "arch/x86/kernel/traps.c:174",
      "file": "arch/x86/kernel/traps.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/traps.c:do_error_trap",
        "arch/x86/kernel/traps.c:do_error_trap"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:early_fixup_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579054448,
      "name": "fixup_bug",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 57
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
int fixup_bug(struct pt_regs * regs, int trapnr)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int fixup_bug(struct pt_regs * regs, int trapnr)
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
int fixup_bug(struct pt_regs * regs, int trapnr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int fixup_bug(struct pt_regs * regs, int trapnr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int fixup_bug(struct pt_regs * regs, int trapnr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int fixup_bug(struct pt_regs * regs, int trapnr)
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
