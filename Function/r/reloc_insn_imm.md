# Function: <code>reloc_insn_imm</code>

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
int reloc_insn_imm(enum aarch64_reloc_op op, __le32 * place, u64 val, int lsb, int len, enum aarch64_insn_imm_type imm_type)
```

```json
{
  "name": "reloc_insn_imm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490294824,
      "name": "reloc_insn_imm",
      "external": false,
      "loc": "arch/arm64/kernel/module.c:193",
      "file": "arch/arm64/kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add",
        "arch/arm64/kernel/module.c:apply_relocate_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490294824,
      "name": "reloc_insn_imm",
      "section": ".text",
      "bind": "STB_LOCAL",
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
int reloc_insn_imm(enum aarch64_reloc_op op, __le32 * place, u64 val, int lsb, int len, enum aarch64_insn_imm_type imm_type)
```
</details>
</li>
</ul>
