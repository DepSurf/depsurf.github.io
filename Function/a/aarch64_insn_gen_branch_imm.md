# Function: <code>aarch64_insn_gen_branch_imm</code>

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
u32 aarch64_insn_gen_branch_imm(long unsigned int pc, long unsigned int addr, enum aarch64_insn_branch_type type)
```

```json
{
  "name": "aarch64_insn_gen_branch_imm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503950248,
      "name": "aarch64_insn_gen_branch_imm",
      "external": true,
      "loc": "arch/arm64/kernel/insn.c:471",
      "file": "arch/arm64/kernel/insn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/ftrace.c:ftrace_disable_ftrace_graph_caller",
        "arch/arm64/kernel/ftrace.c:ftrace_enable_ftrace_graph_caller",
        "arch/arm64/kernel/ftrace.c:ftrace_make_nop",
        "arch/arm64/kernel/ftrace.c:ftrace_make_call",
        "arch/arm64/kernel/ftrace.c:ftrace_update_ftrace_func",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module-plts.c:module_emit_veneer_for_adrp",
        "arch/arm64/kernel/jump_label.c:arch_jump_label_transform",
        "arch/arm64/net/bpf_jit_comp.c:build_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503950248,
      "name": "aarch64_insn_gen_branch_imm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 192
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
u32 aarch64_insn_gen_branch_imm(long unsigned int pc, long unsigned int addr, enum aarch64_insn_branch_type type)
```
</details>
</li>
</ul>
