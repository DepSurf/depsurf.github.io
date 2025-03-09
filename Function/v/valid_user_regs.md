# Function: <code>valid_user_regs</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int valid_user_regs(struct user_pt_regs * regs, struct task_struct * task)
```

```json
{
  "name": "valid_user_regs",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336490217472,
      "name": "valid_user_regs",
      "external": true,
      "loc": "arch/arm64/kernel/ptrace.c:1935",
      "file": "arch/arm64/kernel/ptrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/ptrace.c:compat_gpr_set",
        "arch/arm64/kernel/ptrace.c:gpr_set",
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:do_notify_resume",
        "arch/arm64/kernel/signal.c:restore_sigframe",
        "arch/arm64/kernel/signal.c:restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe",
        "arch/arm64/kernel/signal32.c:compat_restore_sigframe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490217472,
      "name": "valid_user_regs",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 252
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "valid_user_regs",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224422920,
      "name": "valid_user_regs",
      "external": false,
      "loc": "arch/arm/include/asm/ptrace.h:57",
      "file": "arch/arm/kernel/ptrace.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/ptrace.c:arch_ptrace",
        "arch/arm/kernel/ptrace.c:gpr_set"
      ],
      "caller_func": []
    },
    {
      "addr": 3224431252,
      "name": "valid_user_regs",
      "external": false,
      "loc": "arch/arm/include/asm/ptrace.h:57",
      "file": "arch/arm/kernel/signal.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/kernel/signal.c:do_work_pending",
        "arch/arm/kernel/signal.c:restore_sigframe"
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
int valid_user_regs(struct user_pt_regs * regs, struct task_struct * task)
```
</details>
</li>
</ul>
