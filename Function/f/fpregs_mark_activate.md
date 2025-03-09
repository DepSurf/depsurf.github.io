# Function: <code>fpregs_mark_activate</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098624,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:365",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098624,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100608,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:365",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100608,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579113940,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:388",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/fpu/core.c:fpu__clear"
      ],
      "caller_func": [
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113440,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579113568,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:428",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113568,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579120224,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:428",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120224,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 114
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579145680,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:440",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145680,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579187600,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:777",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate",
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579187600,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579243520,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:774",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate",
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579243520,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579249872,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:774",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate",
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579249872,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579279296,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:827",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear_user_states",
        "arch/x86/kernel/fpu/core.c:fpu_swap_kvm_fpstate",
        "arch/x86/kernel/fpu/signal.c:__fpu_restore_sig",
        "arch/x86/kernel/fpu/signal.c:restore_fpregs_from_user"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579279296,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 142
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100992,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:365",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100992,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033408,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:365",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033408,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100544,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:365",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100544,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 140
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
void fpregs_mark_activate()
```

```json
{
  "name": "fpregs_mark_activate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579105040,
      "name": "fpregs_mark_activate",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:365",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/fpu/core.c:fpu__clear",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig",
        "arch/x86/kernel/fpu/signal.c:__fpu__restore_sig"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105040,
      "name": "fpregs_mark_activate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 161
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
void fpregs_mark_activate()
```
</details>
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
void fpregs_mark_activate()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void fpregs_mark_activate()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void fpregs_mark_activate()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void fpregs_mark_activate()
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
