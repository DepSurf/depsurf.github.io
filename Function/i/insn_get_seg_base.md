# Function: <code>insn_get_seg_base</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588820288,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:627",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588820288,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 172
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589198576,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:627",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589198576,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589439920,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:627",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589439920,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 169
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589897920,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:633",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589897920,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590123904,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:633",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590123904,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585128096,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:633",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585128096,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585279376,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:663",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:vc_handle_mmio_movs",
        "arch/x86/kernel/sev-es.c:vc_handle_mmio_movs",
        "arch/x86/kernel/sev-es.c:vc_handle_ioio",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585279376,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585162528,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:659",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162528,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
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
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585615712,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:659",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615712,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 347
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586773232,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:681",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586773232,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595938912,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:681",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595938912,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 463
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
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596457248,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:681",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596457248,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597352272,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:681",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user_inatomic",
        "arch/x86/lib/insn-eval.c:insn_fetch_from_user",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597352272,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 470
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589726160,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:633",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726160,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589451920,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:633",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589451920,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 264
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590169536,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:633",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590169536,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "insn_get_seg_base",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590219984,
      "name": "insn_get_seg_base",
      "external": true,
      "loc": "arch/x86/lib/insn-eval.c:633",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/umip.c:fixup_umip_exception",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219984,
      "name": "insn_get_seg_base",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 212
    }
  ]
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
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long unsigned int insn_get_seg_base(struct pt_regs * regs, int seg_reg_idx)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
