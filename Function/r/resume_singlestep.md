# Function: <code>resume_singlestep</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void resume_singlestep(struct kprobe * p, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "resume_singlestep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579348000,
      "name": "resume_singlestep",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:895",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348000,
      "name": "resume_singlestep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void resume_singlestep(struct kprobe * p, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "resume_singlestep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579405728,
      "name": "resume_singlestep",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:889",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579405728,
      "name": "resume_singlestep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void resume_singlestep(struct kprobe * p, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "resume_singlestep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579473272,
      "name": "resume_singlestep",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:891",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579471888,
      "name": "resume_singlestep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void resume_singlestep(struct kprobe * p, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "resume_singlestep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579566008,
      "name": "resume_singlestep",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:864",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579563968,
      "name": "resume_singlestep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void resume_singlestep(struct kprobe * p, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "resume_singlestep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579578324,
      "name": "resume_singlestep",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:866",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579576288,
      "name": "resume_singlestep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
void resume_singlestep(struct kprobe * p, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "resume_singlestep",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579608116,
      "name": "resume_singlestep",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:901",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606032,
      "name": "resume_singlestep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 69
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void resume_singlestep(struct kprobe * p, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```
</details>
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
