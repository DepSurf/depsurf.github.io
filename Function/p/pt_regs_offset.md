# Function: <code>pt_regs_offset</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int pt_regs_offset(struct pt_regs * regs, int regno)
```

```json
{
  "name": "pt_regs_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586772625,
      "name": "pt_regs_offset",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:440",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_eff_addr_sib",
        "arch/x86/lib/insn-eval.c:get_eff_addr_sib",
        "arch/x86/lib/insn-eval.c:get_eff_addr_modrm",
        "arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:ex_handler_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773136,
      "name": "pt_regs_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int pt_regs_offset(struct pt_regs * regs, int regno)
```

```json
{
  "name": "pt_regs_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595938257,
      "name": "pt_regs_offset",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:440",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_eff_addr_sib",
        "arch/x86/lib/insn-eval.c:get_eff_addr_sib",
        "arch/x86/lib/insn-eval.c:get_eff_addr_modrm",
        "arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:ex_handler_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595938800,
      "name": "pt_regs_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int pt_regs_offset(struct pt_regs * regs, int regno)
```

```json
{
  "name": "pt_regs_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596456593,
      "name": "pt_regs_offset",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:440",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_eff_addr_sib",
        "arch/x86/lib/insn-eval.c:get_eff_addr_sib",
        "arch/x86/lib/insn-eval.c:get_eff_addr_modrm",
        "arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:ex_handler_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596457136,
      "name": "pt_regs_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int pt_regs_offset(struct pt_regs * regs, int regno)
```

```json
{
  "name": "pt_regs_offset",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597351617,
      "name": "pt_regs_offset",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:440",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_eff_addr_sib",
        "arch/x86/lib/insn-eval.c:get_eff_addr_sib",
        "arch/x86/lib/insn-eval.c:get_eff_addr_modrm",
        "arch/x86/lib/insn-eval.c:insn_get_modrm_reg_ptr"
      ],
      "caller_func": [
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:fixup_exception",
        "arch/x86/mm/extable.c:ex_handler_msr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597352160,
      "name": "pt_regs_offset",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int pt_regs_offset(struct pt_regs * regs, int regno)
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
