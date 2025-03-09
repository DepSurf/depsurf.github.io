# Function: <code>fpstate_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579081328,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:210",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_read",
        "arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579081328,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077904,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:224",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077904,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579076608,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:173",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579076608,
      "name": "fpstate_init",
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
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579068608,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:172",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__activate_fpstate_write",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579068608,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579077824,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:172",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_write",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579077824,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579083072,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:173",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_write",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579083072,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579088480,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:171",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_write",
        "arch/x86/kernel/fpu/core.c:fpu__prepare_read",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579088480,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098240,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:149",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098240,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100224,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:149",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100224,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112496,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:155",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112496,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579112720,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:195",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579112720,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579119376,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:195",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579119376,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579144720,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:232",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579144720,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100608,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:149",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100608,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033024,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:149",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033024,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100160,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:149",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100160,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
void fpstate_init(union fpregs_state * state)
```

```json
{
  "name": "fpstate_init",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579104656,
      "name": "fpstate_init",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:149",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/init.c:fpu__init_system",
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/regset.c:xstateregs_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579104656,
      "name": "fpstate_init",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 71
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
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
void fpstate_init(union fpregs_state * state)
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
void fpstate_init(union fpregs_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void fpstate_init(union fpregs_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void fpstate_init(union fpregs_state * state)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void fpstate_init(union fpregs_state * state)
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
