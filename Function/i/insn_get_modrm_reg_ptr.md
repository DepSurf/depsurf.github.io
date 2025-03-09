# Function: <code>insn_get_modrm_reg_ptr</code>

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
long unsigned int * insn_get_modrm_reg_ptr(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "insn_get_modrm_reg_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "insn_get_modrm_reg_ptr",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:885",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594207356,
      "name": "insn_get_modrm_reg_ptr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071586775712,
      "name": "insn_get_modrm_reg_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int * insn_get_modrm_reg_ptr(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "insn_get_modrm_reg_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "insn_get_modrm_reg_ptr",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:885",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/mm/extable.c:ex_handler_zeropad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596376340,
      "name": "insn_get_modrm_reg_ptr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071595941488,
      "name": "insn_get_modrm_reg_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int * insn_get_modrm_reg_ptr(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "insn_get_modrm_reg_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "insn_get_modrm_reg_ptr",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:885",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/mm/extable.c:ex_handler_zeropad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596905717,
      "name": "insn_get_modrm_reg_ptr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071596459792,
      "name": "insn_get_modrm_reg_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
long unsigned int * insn_get_modrm_reg_ptr(struct insn * insn, struct pt_regs * regs)
```

```json
{
  "name": "insn_get_modrm_reg_ptr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "insn_get_modrm_reg_ptr",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:885",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/mm/extable.c:ex_handler_zeropad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597830810,
      "name": "insn_get_modrm_reg_ptr.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    },
    {
      "addr": 18446744071597354816,
      "name": "insn_get_modrm_reg_ptr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 178
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
long unsigned int * insn_get_modrm_reg_ptr(struct insn * insn, struct pt_regs * regs)
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
