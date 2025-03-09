# Function: <code>emit_insn_suffix</code>

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
void emit_insn_suffix(u8 * * pprog, u32 ptr_reg, u32 val_reg, int off)
```

```json
{
  "name": "emit_insn_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579496967,
      "name": "emit_insn_suffix",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:700",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482688,
      "name": "emit_insn_suffix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
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
void emit_insn_suffix(u8 * * pprog, u32 ptr_reg, u32 val_reg, int off)
```

```json
{
  "name": "emit_insn_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579567298,
      "name": "emit_insn_suffix",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:691",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:emit_ldx"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579548416,
      "name": "emit_insn_suffix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 284
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
void emit_insn_suffix(u8 * * pprog, u32 ptr_reg, u32 val_reg, int off)
```

```json
{
  "name": "emit_insn_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579656864,
      "name": "emit_insn_suffix",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:692",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:emit_ldx"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579637248,
      "name": "emit_insn_suffix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void emit_insn_suffix(u8 * * pprog, u32 ptr_reg, u32 val_reg, int off)
```

```json
{
  "name": "emit_insn_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579775403,
      "name": "emit_insn_suffix",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:705",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:emit_ldx"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579754432,
      "name": "emit_insn_suffix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void emit_insn_suffix(u8 * * pprog, u32 ptr_reg, u32 val_reg, int off)
```

```json
{
  "name": "emit_insn_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579822139,
      "name": "emit_insn_suffix",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:705",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:emit_ldx"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579801008,
      "name": "emit_insn_suffix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void emit_insn_suffix(u8 * * pprog, u32 ptr_reg, u32 val_reg, int off)
```

```json
{
  "name": "emit_insn_suffix",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579844656,
      "name": "emit_insn_suffix",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:871",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:restore_regs"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:save_args",
        "arch/x86/net/bpf_jit_comp.c:save_args",
        "arch/x86/net/bpf_jit_comp.c:save_args",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579834272,
      "name": "emit_insn_suffix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
void emit_insn_suffix(u8 * * pprog, u32 ptr_reg, u32 val_reg, int off)
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
