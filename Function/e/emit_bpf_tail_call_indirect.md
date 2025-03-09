# Function: <code>emit_bpf_tail_call_indirect</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void emit_bpf_tail_call_indirect(u8 * * pprog)
```

```json
{
  "name": "emit_bpf_tail_call_indirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499120,
      "name": "emit_bpf_tail_call_indirect",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:354",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579499120,
      "name": "emit_bpf_tail_call_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 186
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
void emit_bpf_tail_call_indirect(u8 * * pprog, bool * callee_regs_used, u32 stack_depth)
```

```json
{
  "name": "emit_bpf_tail_call_indirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482192,
      "name": "emit_bpf_tail_call_indirect",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:405",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482192,
      "name": "emit_bpf_tail_call_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 355
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
void emit_bpf_tail_call_indirect(u8 * * pprog, bool * callee_regs_used, u32 stack_depth)
```

```json
{
  "name": "emit_bpf_tail_call_indirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579483328,
      "name": "emit_bpf_tail_call_indirect",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:417",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579483328,
      "name": "emit_bpf_tail_call_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 350
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_bpf_tail_call_indirect",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579558524,
      "name": "emit_bpf_tail_call_indirect",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:413",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void emit_bpf_tail_call_indirect(u8 * * pprog, bool * callee_regs_used, u32 stack_depth, u8 * ip, struct jit_context * ctx)
```

```json
{
  "name": "emit_bpf_tail_call_indirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639072,
      "name": "emit_bpf_tail_call_indirect",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:457",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639072,
      "name": "emit_bpf_tail_call_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void emit_bpf_tail_call_indirect(u8 * * pprog, bool * callee_regs_used, u32 stack_depth, u8 * ip, struct jit_context * ctx)
```

```json
{
  "name": "emit_bpf_tail_call_indirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756704,
      "name": "emit_bpf_tail_call_indirect",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:470",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756704,
      "name": "emit_bpf_tail_call_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
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
void emit_bpf_tail_call_indirect(u8 * * pprog, bool * callee_regs_used, u32 stack_depth, u8 * ip, struct jit_context * ctx)
```

```json
{
  "name": "emit_bpf_tail_call_indirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803296,
      "name": "emit_bpf_tail_call_indirect",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:470",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803296,
      "name": "emit_bpf_tail_call_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 448
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
void emit_bpf_tail_call_indirect(struct bpf_prog * bpf_prog, u8 * * pprog, bool * callee_regs_used, u32 stack_depth, u8 * ip, struct jit_context * ctx)
```

```json
{
  "name": "emit_bpf_tail_call_indirect",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emit_bpf_tail_call_indirect",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:592",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838304,
      "name": "emit_bpf_tail_call_indirect",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 535
    },
    {
      "addr": 18446744071597387251,
      "name": "emit_bpf_tail_call_indirect.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 41
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void emit_bpf_tail_call_indirect(u8 * * pprog)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * callee_regs_used</code>
</li>
<li>
<b>Param added. </b>
<code>u32 stack_depth</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void emit_bpf_tail_call_indirect(u8 * * pprog, bool * callee_regs_used, u32 stack_depth)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void emit_bpf_tail_call_indirect(u8 * * pprog, bool * callee_regs_used, u32 stack_depth, u8 * ip, struct jit_context * ctx)
```
</details>
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct bpf_prog * bpf_prog</code>
</li>
<li>
<b>Param reordered. </b>
<code>pprog, callee_regs_used, stack_depth, ip, ctx</code> ➡️ <code>bpf_prog, pprog, callee_regs_used, stack_depth, ip, ctx</code>
</li>
</ul>
</details>
</li>
</ul>
