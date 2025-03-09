# Function: <code>emit_mov_imm64</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579407270,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:369",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579438417,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:369",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579454796,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:338",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579480822,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:338",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
```

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579499488,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:524",
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
      "addr": 18446744071579499488,
      "name": "emit_mov_imm64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
```

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579480304,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:642",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579480304,
      "name": "emit_mov_imm64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
```

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579482272,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:657",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482272,
      "name": "emit_mov_imm64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 173
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
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
```

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579551760,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:650",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579551760,
      "name": "emit_mov_imm64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 233
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
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
```

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579641440,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:651",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071579641440,
      "name": "emit_mov_imm64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
```

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579759248,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:664",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071579759248,
      "name": "emit_mov_imm64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
```

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579805824,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:664",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
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
      "addr": 18446744071579805824,
      "name": "emit_mov_imm64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
```

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579840928,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:798",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:__arch_prepare_bpf_trampoline",
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579840928,
      "name": "emit_mov_imm64",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 264
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579454486,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:338",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579383462,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:338",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579454406,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:338",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "emit_mov_imm64",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579486150,
      "name": "emit_mov_imm64",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:338",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void emit_mov_imm64(u8 * * pprog, u32 dst_reg, const u32 imm32_hi, const u32 imm32_lo)
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
