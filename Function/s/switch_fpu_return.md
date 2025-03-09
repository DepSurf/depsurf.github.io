# Function: <code>switch_fpu_return</code>

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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579098768,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:338",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579098768,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 287
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100752,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:338",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100752,
      "name": "switch_fpu_return",
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579113232,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:361",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__prepare_exit_to_usermode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579113232,
      "name": "switch_fpu_return",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579114032,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:401",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:exit_to_user_mode_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579114032,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579120688,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:401",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:exit_to_user_mode_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579120688,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 179
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579145872,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:413",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:exit_to_user_mode_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579145872,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 189
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579185360,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:750",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:exit_to_user_mode_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579185360,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 230
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579240880,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:747",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:exit_to_user_mode_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579240880,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579247536,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:747",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:exit_to_user_mode_prepare"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579247536,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579276496,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:782",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/common.c:irqentry_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode",
        "kernel/entry/common.c:syscall_exit_to_user_mode_work"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579276496,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 233
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579101136,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:338",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579101136,
      "name": "switch_fpu_return",
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579033552,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:338",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579033552,
      "name": "switch_fpu_return",
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579100688,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:338",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579100688,
      "name": "switch_fpu_return",
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
void switch_fpu_return()
```

```json
{
  "name": "switch_fpu_return",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579105216,
      "name": "switch_fpu_return",
      "external": true,
      "loc": "arch/x86/kernel/fpu/core.c:338",
      "file": "arch/x86/kernel/fpu/core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579105216,
      "name": "switch_fpu_return",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 320
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
void switch_fpu_return()
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
void switch_fpu_return()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void switch_fpu_return()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void switch_fpu_return()
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void switch_fpu_return()
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
