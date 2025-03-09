# Function: <code>kprobe_post_process</code>

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
void kprobe_post_process(struct kprobe * cur, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "kprobe_post_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579348544,
      "name": "kprobe_post_process",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:822",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579348544,
      "name": "kprobe_post_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void kprobe_post_process(struct kprobe * cur, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "kprobe_post_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579406256,
      "name": "kprobe_post_process",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:816",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579406256,
      "name": "kprobe_post_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 109
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
void kprobe_post_process(struct kprobe * cur, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "kprobe_post_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579473302,
      "name": "kprobe_post_process",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:814",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler",
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579472384,
      "name": "kprobe_post_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void kprobe_post_process(struct kprobe * cur, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "kprobe_post_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579566038,
      "name": "kprobe_post_process",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:787",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler",
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579564736,
      "name": "kprobe_post_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void kprobe_post_process(struct kprobe * cur, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "kprobe_post_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579578354,
      "name": "kprobe_post_process",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:789",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler",
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579577056,
      "name": "kprobe_post_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void kprobe_post_process(struct kprobe * cur, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
```

```json
{
  "name": "kprobe_post_process",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579608146,
      "name": "kprobe_post_process",
      "external": false,
      "loc": "arch/x86/kernel/kprobes/core.c:824",
      "file": "arch/x86/kernel/kprobes/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler",
        "arch/x86/kernel/kprobes/core.c:kprobe_int3_handler"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579606848,
      "name": "kprobe_post_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
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
void kprobe_post_process(struct kprobe * cur, struct pt_regs * regs, struct kprobe_ctlblk * kcb)
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
