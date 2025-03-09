# Function: <code>emit_stx</code>

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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```

```json
{
  "name": "emit_stx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579511290,
      "name": "emit_stx",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:606",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579500320,
      "name": "emit_stx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 455
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```

```json
{
  "name": "emit_stx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579493764,
      "name": "emit_stx",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:724",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579481136,
      "name": "emit_stx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 450
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```

```json
{
  "name": "emit_stx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579496967,
      "name": "emit_stx",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:767",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579484720,
      "name": "emit_stx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 482
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```

```json
{
  "name": "emit_stx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579567170,
      "name": "emit_stx",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:769",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579553360,
      "name": "emit_stx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 491
    },
    {
      "addr": 18446744071592097256,
      "name": "emit_stx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```

```json
{
  "name": "emit_stx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579656166,
      "name": "emit_stx",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:770",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579643232,
      "name": "emit_stx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071593864508,
      "name": "emit_stx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```

```json
{
  "name": "emit_stx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579774470,
      "name": "emit_stx",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:783",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579761312,
      "name": "emit_stx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 510
    },
    {
      "addr": 18446744071595972842,
      "name": "emit_stx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```

```json
{
  "name": "emit_stx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579821262,
      "name": "emit_stx",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:783",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579807744,
      "name": "emit_stx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 489
    },
    {
      "addr": 18446744071596490469,
      "name": "emit_stx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```

```json
{
  "name": "emit_stx",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579843754,
      "name": "emit_stx",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:972",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:save_args",
        "arch/x86/net/bpf_jit_comp.c:save_args"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579842752,
      "name": "emit_stx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 478
    },
    {
      "addr": 18446744071597387325,
      "name": "emit_stx.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void emit_stx(u8 * * pprog, u32 size, u32 dst_reg, u32 src_reg, int off)
```
</details>
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
