# Function: <code>emit_bpf_tail_call_direct</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_bpf_tail_call_direct",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579504979,
      "name": "emit_bpf_tail_call_direct",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:421",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor * poke, u8 * * pprog, int addr, u8 * image, bool * callee_regs_used, u32 stack_depth)
```

```json
{
  "name": "emit_bpf_tail_call_direct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emit_bpf_tail_call_direct",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:495",
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
      "addr": 18446744071579482560,
      "name": "emit_bpf_tail_call_direct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 336
    },
    {
      "addr": 18446744071591275992,
      "name": "emit_bpf_tail_call_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor * poke, u8 * * pprog, int addr, u8 * image, bool * callee_regs_used, u32 stack_depth)
```

```json
{
  "name": "emit_bpf_tail_call_direct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emit_bpf_tail_call_direct",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:507",
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
      "addr": 18446744071579484384,
      "name": "emit_bpf_tail_call_direct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 326
    },
    {
      "addr": 18446744071591218867,
      "name": "emit_bpf_tail_call_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor * poke, u8 * * pprog, int addr, u8 * image, bool * callee_regs_used, u32 stack_depth)
```

```json
{
  "name": "emit_bpf_tail_call_direct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emit_bpf_tail_call_direct",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:502",
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
      "addr": 18446744071579549120,
      "name": "emit_bpf_tail_call_direct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 319
    },
    {
      "addr": 18446744071592096916,
      "name": "emit_bpf_tail_call_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor * poke, u8 * * pprog, u8 * ip, bool * callee_regs_used, u32 stack_depth, struct jit_context * ctx)
```

```json
{
  "name": "emit_bpf_tail_call_direct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emit_bpf_tail_call_direct",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:531",
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
      "addr": 18446744071579638064,
      "name": "emit_bpf_tail_call_direct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 389
    },
    {
      "addr": 18446744071593864256,
      "name": "emit_bpf_tail_call_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor * poke, u8 * * pprog, u8 * ip, bool * callee_regs_used, u32 stack_depth, struct jit_context * ctx)
```

```json
{
  "name": "emit_bpf_tail_call_direct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579755440,
      "name": "emit_bpf_tail_call_direct",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:544",
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
      "addr": 18446744071579755440,
      "name": "emit_bpf_tail_call_direct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor * poke, u8 * * pprog, u8 * ip, bool * callee_regs_used, u32 stack_depth, struct jit_context * ctx)
```

```json
{
  "name": "emit_bpf_tail_call_direct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579802032,
      "name": "emit_bpf_tail_call_direct",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:544",
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
      "addr": 18446744071579802032,
      "name": "emit_bpf_tail_call_direct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 411
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
void emit_bpf_tail_call_direct(struct bpf_prog * bpf_prog, struct bpf_jit_poke_descriptor * poke, u8 * * pprog, u8 * ip, bool * callee_regs_used, u32 stack_depth, struct jit_context * ctx)
```

```json
{
  "name": "emit_bpf_tail_call_direct",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emit_bpf_tail_call_direct",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:672",
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
      "addr": 18446744071579837536,
      "name": "emit_bpf_tail_call_direct",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 507
    },
    {
      "addr": 18446744071597387214,
      "name": "emit_bpf_tail_call_direct.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 37
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
void emit_bpf_tail_call_direct(struct bpf_jit_poke_descriptor * poke, u8 * * pprog, int addr, u8 * image, bool * callee_regs_used, u32 stack_depth)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>u8 * ip</code>
</li>
<li>
<b>Param added. </b>
<code>struct jit_context * ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>u8 * image</code>
</li>
<li>
<b>Param reordered. </b>
<code>poke, pprog, addr, image, callee_regs_used, stack_depth</code> ➡️ <code>poke, pprog, ip, callee_regs_used, stack_depth, ctx</code>
</li>
</ul>
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
<code>poke, pprog, ip, callee_regs_used, stack_depth, ctx</code> ➡️ <code>bpf_prog, poke, pprog, ip, callee_regs_used, stack_depth, ctx</code>
</li>
</ul>
</details>
</li>
</ul>
