# Function: <code>syscall_exit_to_user_mode</code>

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
void syscall_exit_to_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "syscall_exit_to_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591659904,
      "name": "syscall_exit_to_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:298",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591659904,
      "name": "syscall_exit_to_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void syscall_exit_to_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "syscall_exit_to_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591603584,
      "name": "syscall_exit_to_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:299",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591603584,
      "name": "syscall_exit_to_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
void syscall_exit_to_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "syscall_exit_to_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592776464,
      "name": "syscall_exit_to_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:297",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592776464,
      "name": "syscall_exit_to_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
void syscall_exit_to_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "syscall_exit_to_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594674144,
      "name": "syscall_exit_to_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:291",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594674144,
      "name": "syscall_exit_to_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 74
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
void syscall_exit_to_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "syscall_exit_to_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596408320,
      "name": "syscall_exit_to_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:293",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596408320,
      "name": "syscall_exit_to_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 77
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
void syscall_exit_to_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "syscall_exit_to_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596940336,
      "name": "syscall_exit_to_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:294",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_syscall_32",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/kernel/process.c:ret_from_fork",
        "arch/x86/kernel/process.c:ret_from_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596940336,
      "name": "syscall_exit_to_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 82
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
void syscall_exit_to_user_mode(struct pt_regs * regs)
```

```json
{
  "name": "syscall_exit_to_user_mode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597865680,
      "name": "syscall_exit_to_user_mode",
      "external": true,
      "loc": "kernel/entry/common.c:209",
      "file": "kernel/entry/common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/entry/common.c:__do_fast_syscall_32",
        "arch/x86/entry/common.c:do_int80_emulation",
        "arch/x86/entry/common.c:do_syscall_64",
        "arch/x86/kernel/process.c:ret_from_fork",
        "arch/x86/kernel/process.c:ret_from_fork"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597865680,
      "name": "syscall_exit_to_user_mode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 604
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
void syscall_exit_to_user_mode(struct pt_regs * regs)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
