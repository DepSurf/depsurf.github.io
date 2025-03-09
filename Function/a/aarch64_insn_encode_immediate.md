# Function: <code>aarch64_insn_encode_immediate</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
u32 aarch64_insn_encode_immediate(enum aarch64_insn_imm_type type, u32 insn, u64 imm)
```

```json
{
  "name": "aarch64_insn_encode_immediate",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503950072,
      "name": "aarch64_insn_encode_immediate",
      "external": true,
      "loc": "arch/arm64/kernel/insn.c:317",
      "file": "arch/arm64/kernel/insn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_extr",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_extr",
        "arch/arm64/kernel/insn.c:aarch64_encode_immediate",
        "arch/arm64/kernel/insn.c:aarch64_encode_immediate",
        "arch/arm64/kernel/insn.c:aarch64_encode_immediate",
        "arch/arm64/kernel/insn.c:aarch64_insn_adrp_set_offset",
        "arch/arm64/kernel/insn.c:aarch64_set_branch_offset",
        "arch/arm64/kernel/insn.c:aarch64_set_branch_offset",
        "arch/arm64/kernel/insn.c:aarch64_set_branch_offset",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_adr",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_logical_shifted_reg",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_add_sub_shifted_reg",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_movewide",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_bitfield",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_bitfield",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_add_sub_imm",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_prefetch",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_load_store_pair",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_cond_branch_imm",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_comp_branch_imm",
        "arch/arm64/kernel/insn.c:aarch64_insn_gen_branch_imm",
        "arch/arm64/kernel/module.c:reloc_insn_imm",
        "arch/arm64/kernel/module.c:reloc_insn_movw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503950072,
      "name": "aarch64_insn_encode_immediate",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
u32 aarch64_insn_encode_immediate(enum aarch64_insn_imm_type type, u32 insn, u64 imm)
```
</details>
</li>
</ul>
