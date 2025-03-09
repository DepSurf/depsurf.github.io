# Function: <code>emit_mov_i</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void emit_mov_i(const u8 rd, u32 val, struct jit_ctx * ctx)
```

```json
{
  "name": "emit_mov_i",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3224545512,
      "name": "emit_mov_i",
      "external": false,
      "loc": "arch/arm/net/bpf_jit_32.c:425",
      "file": "arch/arm/net/bpf_jit_32.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_prologue",
        "arch/arm/net/bpf_jit_32.c:emit_str_r",
        "arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64",
        "arch/arm/net/bpf_jit_32.c:emit_a32_alu_r64",
        "arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64",
        "arch/arm/net/bpf_jit_32.c:emit_a32_mov_i64"
      ],
      "caller_func": [
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn",
        "arch/arm/net/bpf_jit_32.c:build_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3224537540,
      "name": "emit_mov_i",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 228
    }
  ]
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
void emit_mov_i(const u8 rd, u32 val, struct jit_ctx * ctx)
```
</details>
</li>
</ul>
