# Function: <code>insn_decode</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
bool insn_decode(struct insn * insn, struct pt_regs * regs, unsigned char * buf, int buf_size)
```

```json
{
  "name": "insn_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585281744,
      "name": "insn_decode",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:1508",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/kernel/sev-es.c:vc_decode_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585281744,
      "name": "insn_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 129
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
int insn_decode(struct insn * insn, const void * kaddr, int buf_len, enum insn_mode m)
```

```json
{
  "name": "insn_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585168448,
      "name": "insn_decode",
      "external": true,
      "loc": "arch/x86/lib/insn.c:735",
      "file": "arch/x86/lib/insn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/alternative.c:text_poke_loc_init",
        "arch/x86/kernel/alternative.c:optimize_nops",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/kprobes/core.c:can_probe",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn",
        "arch/x86/kernel/sev.c:vc_init_em_ctxt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585168448,
      "name": "insn_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int insn_decode(struct insn * insn, const void * kaddr, int buf_len, enum insn_mode m)
```

```json
{
  "name": "insn_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585622144,
      "name": "insn_decode",
      "external": true,
      "loc": "arch/x86/lib/insn.c:736",
      "file": "arch/x86/lib/insn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/jump_label.c:arch_jump_entry_size",
        "arch/x86/kernel/alternative.c:text_poke_loc_init",
        "arch/x86/kernel/alternative.c:optimize_nops",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/kprobes/core.c:can_probe",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn",
        "arch/x86/kernel/sev.c:vc_init_em_ctxt"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585622144,
      "name": "insn_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 239
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
int insn_decode(struct insn * insn, const void * kaddr, int buf_len, enum insn_mode m)
```

```json
{
  "name": "insn_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586781056,
      "name": "insn_decode",
      "external": true,
      "loc": "arch/x86/lib/insn.c:736",
      "file": "arch/x86/lib/insn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/jump_label.c:arch_jump_entry_size",
        "arch/x86/kernel/alternative.c:text_poke_loc_init",
        "arch/x86/kernel/alternative.c:apply_returns",
        "arch/x86/kernel/alternative.c:apply_retpolines",
        "arch/x86/kernel/alternative.c:optimize_nops",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/kprobes/core.c:__copy_instruction",
        "arch/x86/kernel/kprobes/core.c:can_probe",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/uprobes.c:arch_uprobe_analyze_insn",
        "arch/x86/kernel/sev.c:vc_decode_insn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586781056,
      "name": "insn_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int insn_decode(struct insn * insn, const void * kaddr, int buf_len, enum insn_mode m)
```

```json
{
  "name": "insn_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595947088,
      "name": "insn_decode",
      "external": true,
      "loc": "arch/x86/lib/insn.c:736",
      "file": "arch/x86/lib/insn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/jump_label.c:arch_jump_entry_size",
        "arch/x86/kernel/alternative.c:text_poke_loc_init",
        "arch/x86/kernel/alternative.c:apply_returns",
        "arch/x86/kernel/alternative.c:apply_retpolines",
        "arch/x86/kernel/alternative.c:optimize_nops",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/kprobes/core.c:__copy_instruction",
        "arch/x86/kernel/kprobes/core.c:can_probe",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/uprobes.c:uprobe_init_insn",
        "arch/x86/kernel/sev.c:vc_decode_insn",
        "arch/x86/kernel/callthunks.c:call_get_dest",
        "arch/x86/mm/extable.c:ex_handler_zeropad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595947088,
      "name": "insn_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int insn_decode(struct insn * insn, const void * kaddr, int buf_len, enum insn_mode m)
```

```json
{
  "name": "insn_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596465360,
      "name": "insn_decode",
      "external": true,
      "loc": "arch/x86/lib/insn.c:736",
      "file": "arch/x86/lib/insn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/jump_label.c:arch_jump_entry_size",
        "arch/x86/kernel/alternative.c:text_poke_loc_init",
        "arch/x86/kernel/alternative.c:apply_returns",
        "arch/x86/kernel/alternative.c:apply_retpolines",
        "arch/x86/kernel/alternative.c:apply_relocation",
        "arch/x86/kernel/alternative.c:optimize_nops",
        "arch/x86/kernel/alternative.c:skip_nops",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/kprobes/core.c:__copy_instruction",
        "arch/x86/kernel/kprobes/core.c:can_probe",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/uprobes.c:uprobe_init_insn",
        "arch/x86/kernel/sev.c:vc_init_em_ctxt",
        "arch/x86/kernel/callthunks.c:call_get_dest",
        "arch/x86/mm/extable.c:ex_handler_zeropad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596465360,
      "name": "insn_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
int insn_decode(struct insn * insn, const void * kaddr, int buf_len, enum insn_mode m)
```

```json
{
  "name": "insn_decode",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597360368,
      "name": "insn_decode",
      "external": true,
      "loc": "arch/x86/lib/insn.c:736",
      "file": "arch/x86/lib/insn.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/coco/tdx/tdx.c:handle_mmio",
        "arch/x86/kernel/traps.c:get_kernel_gp_address",
        "arch/x86/kernel/jump_label.c:arch_jump_entry_size",
        "arch/x86/kernel/alternative.c:text_poke_loc_init",
        "arch/x86/kernel/alternative.c:apply_returns",
        "arch/x86/kernel/alternative.c:apply_retpolines",
        "arch/x86/kernel/alternative.c:apply_relocation",
        "arch/x86/kernel/alternative.c:optimize_nops",
        "arch/x86/kernel/alternative.c:skip_nops",
        "arch/x86/kernel/cpu/mce/severity.c:is_copy_from_user",
        "arch/x86/kernel/kprobes/core.c:__copy_instruction",
        "arch/x86/kernel/kprobes/core.c:can_probe",
        "arch/x86/kernel/kprobes/opt.c:can_optimize",
        "arch/x86/kernel/uprobes.c:uprobe_init_insn",
        "arch/x86/kernel/sev.c:vc_init_em_ctxt",
        "arch/x86/kernel/callthunks.c:call_get_dest",
        "arch/x86/mm/extable.c:ex_handler_zeropad"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597360368,
      "name": "insn_decode",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 137
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
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
bool insn_decode(struct insn * insn, struct pt_regs * regs, unsigned char * buf, int buf_size)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void * kaddr</code>
</li>
<li>
<b>Param added. </b>
<code>int buf_len</code>
</li>
<li>
<b>Param added. </b>
<code>enum insn_mode m</code>
</li>
<li>
<b>Param removed. </b>
<code>struct pt_regs * regs</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char * buf</code>
</li>
<li>
<b>Param removed. </b>
<code>int buf_size</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>int</code>
</li>
</ul>
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
