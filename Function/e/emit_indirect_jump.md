# Function: <code>emit_indirect_jump</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void emit_indirect_jump(u8 * * pprog, int reg, u8 * ip)
```

```json
{
  "name": "emit_indirect_jump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "emit_indirect_jump",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:411",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579638880,
      "name": "emit_indirect_jump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 177
    },
    {
      "addr": 18446744071593864319,
      "name": "emit_indirect_jump.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
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
void emit_indirect_jump(u8 * * pprog, int reg, u8 * ip)
```

```json
{
  "name": "emit_indirect_jump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579756464,
      "name": "emit_indirect_jump",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:419",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579756464,
      "name": "emit_indirect_jump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void emit_indirect_jump(u8 * * pprog, int reg, u8 * ip)
```

```json
{
  "name": "emit_indirect_jump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579803056,
      "name": "emit_indirect_jump",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:419",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579803056,
      "name": "emit_indirect_jump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
void emit_indirect_jump(u8 * * pprog, int reg, u8 * ip)
```

```json
{
  "name": "emit_indirect_jump",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579838064,
      "name": "emit_indirect_jump",
      "external": false,
      "loc": "arch/x86/net/bpf_jit_comp.c:541",
      "file": "arch/x86/net/bpf_jit_comp.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_dispatcher",
        "arch/x86/net/bpf_jit_comp.c:emit_bpf_tail_call_indirect"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579838064,
      "name": "emit_indirect_jump",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void emit_indirect_jump(u8 * * pprog, int reg, u8 * ip)
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
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
