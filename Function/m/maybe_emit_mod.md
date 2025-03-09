# Function: <code>maybe_emit_mod</code>

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
void maybe_emit_mod(u8 * * pprog, u32 dst_reg, u32 src_reg, bool is64)
```

```json
{
  "name": "maybe_emit_mod",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071579491434,
      "name": "maybe_emit_mod",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:723",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/net/bpf_jit_comp.c:do_jit"
      ],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579482784,
      "name": "maybe_emit_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void maybe_emit_mod(u8 * * pprog, u32 dst_reg, u32 src_reg, bool is64)
```

```json
{
  "name": "maybe_emit_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579550512,
      "name": "maybe_emit_mod",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:713",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579550512,
      "name": "maybe_emit_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 95
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
void maybe_emit_mod(u8 * * pprog, u32 dst_reg, u32 src_reg, bool is64)
```

```json
{
  "name": "maybe_emit_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579639520,
      "name": "maybe_emit_mod",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:714",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579639520,
      "name": "maybe_emit_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void maybe_emit_mod(u8 * * pprog, u32 dst_reg, u32 src_reg, bool is64)
```

```json
{
  "name": "maybe_emit_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579757824,
      "name": "maybe_emit_mod",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:727",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579757824,
      "name": "maybe_emit_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void maybe_emit_mod(u8 * * pprog, u32 dst_reg, u32 src_reg, bool is64)
```

```json
{
  "name": "maybe_emit_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579804400,
      "name": "maybe_emit_mod",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:727",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579804400,
      "name": "maybe_emit_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void maybe_emit_mod(u8 * * pprog, u32 dst_reg, u32 src_reg, bool is64)
```

```json
{
  "name": "maybe_emit_mod",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838864,
      "name": "maybe_emit_mod",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:893",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:do_jit",
        "arch/x86/net/bpf_jit_comp.c:emit_atomic"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838864,
      "name": "maybe_emit_mod",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 123
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
void maybe_emit_mod(u8 * * pprog, u32 dst_reg, u32 src_reg, bool is64)
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
