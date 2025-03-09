# Function: <code>arch_syscall_is_vdso_sigreturn</code>

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
bool arch_syscall_is_vdso_sigreturn(struct pt_regs * regs)
```

```json
{
  "name": "arch_syscall_is_vdso_sigreturn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578865232,
      "name": "arch_syscall_is_vdso_sigreturn",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:422",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865232,
      "name": "arch_syscall_is_vdso_sigreturn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
bool arch_syscall_is_vdso_sigreturn(struct pt_regs * regs)
```

```json
{
  "name": "arch_syscall_is_vdso_sigreturn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578865136,
      "name": "arch_syscall_is_vdso_sigreturn",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:422",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865136,
      "name": "arch_syscall_is_vdso_sigreturn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
bool arch_syscall_is_vdso_sigreturn(struct pt_regs * regs)
```

```json
{
  "name": "arch_syscall_is_vdso_sigreturn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578866688,
      "name": "arch_syscall_is_vdso_sigreturn",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:422",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578866688,
      "name": "arch_syscall_is_vdso_sigreturn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 94
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
bool arch_syscall_is_vdso_sigreturn(struct pt_regs * regs)
```

```json
{
  "name": "arch_syscall_is_vdso_sigreturn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578862848,
      "name": "arch_syscall_is_vdso_sigreturn",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:422",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578862848,
      "name": "arch_syscall_is_vdso_sigreturn",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs * regs)
```

```json
{
  "name": "arch_syscall_is_vdso_sigreturn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578865280,
      "name": "arch_syscall_is_vdso_sigreturn",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:399",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578865280,
      "name": "arch_syscall_is_vdso_sigreturn",
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
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs * regs)
```

```json
{
  "name": "arch_syscall_is_vdso_sigreturn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578863232,
      "name": "arch_syscall_is_vdso_sigreturn",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:400",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578863232,
      "name": "arch_syscall_is_vdso_sigreturn",
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
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
bool arch_syscall_is_vdso_sigreturn(struct pt_regs * regs)
```

```json
{
  "name": "arch_syscall_is_vdso_sigreturn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071578873744,
      "name": "arch_syscall_is_vdso_sigreturn",
      "external": true,
      "loc": "arch/x86/entry/vdso/vma.c:400",
      "file": "arch/x86/entry/vdso/vma.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/entry/syscall_user_dispatch.c:syscall_user_dispatch"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071578873744,
      "name": "arch_syscall_is_vdso_sigreturn",
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
bool arch_syscall_is_vdso_sigreturn(struct pt_regs * regs)
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
