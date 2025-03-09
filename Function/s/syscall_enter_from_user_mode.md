# Function: <code>syscall_enter_from_user_mode</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
long int syscall_enter_from_user_mode(struct pt_regs * regs, long int syscall)
```

```json
{
  "name": "syscall_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659808,
      "name": "syscall_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:99",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659808,
      "name": "syscall_enter_from_user_mode",
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
long int syscall_enter_from_user_mode(struct pt_regs * regs, long int syscall)
```

```json
{
  "name": "syscall_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603488,
      "name": "syscall_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:100",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603488,
      "name": "syscall_enter_from_user_mode",
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
long int syscall_enter_from_user_mode(struct pt_regs * regs, long int syscall)
```

```json
{
  "name": "syscall_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776368,
      "name": "syscall_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:100",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776368,
      "name": "syscall_enter_from_user_mode",
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
long int syscall_enter_from_user_mode(struct pt_regs * regs, long int syscall)
```

```json
{
  "name": "syscall_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594674032,
      "name": "syscall_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:102",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594674032,
      "name": "syscall_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
long int syscall_enter_from_user_mode(struct pt_regs * regs, long int syscall)
```

```json
{
  "name": "syscall_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596408128,
      "name": "syscall_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:104",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596408128,
      "name": "syscall_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
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
long int syscall_enter_from_user_mode(struct pt_regs * regs, long int syscall)
```

```json
{
  "name": "syscall_enter_from_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596940128,
      "name": "syscall_enter_from_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:104",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596940128,
      "name": "syscall_enter_from_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 92
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "syscall_enter_from_user_mode",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597832005,
      "name": "syscall_enter_from_user_mode",
      "external": false,
      "loc": "include/linux/entry-common.h:190",
      "file": "arch/x86/entry/common.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/x86/entry/common.c:do_syscall_64"
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
long int syscall_enter_from_user_mode(struct pt_regs * regs, long int syscall)
```
</details>
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
<details>
<summary>Removed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ➖</summary>

```c
long int syscall_enter_from_user_mode(struct pt_regs * regs, long int syscall)
```
</details>
</li>
</ul>
