# Function: <code>get_segment_selector</code>

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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588821317,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:318",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588818960,
      "name": "get_segment_selector.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589199477,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:318",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589197152,
      "name": "get_segment_selector.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589441029,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:318",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589438608,
      "name": "get_segment_selector.isra.2",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589899155,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:320",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589896560,
      "name": "get_segment_selector.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590125139,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:320",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590122544,
      "name": "get_segment_selector.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585129635,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:320",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585126544,
      "name": "get_segment_selector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585280691,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:345",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277440,
      "name": "get_segment_selector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585164131,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:345",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585160928,
      "name": "get_segment_selector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585617347,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:345",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params",
        "arch/x86/lib/insn-eval.c:insn_get_seg_base"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585614032,
      "name": "get_segment_selector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586775243,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:343",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586771168,
      "name": "get_segment_selector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071595940971,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:343",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595936720,
      "name": "get_segment_selector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596459275,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:343",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596455072,
      "name": "get_segment_selector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071597354299,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:343",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597350096,
      "name": "get_segment_selector",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589727395,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:320",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589724800,
      "name": "get_segment_selector.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589453091,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:320",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589450576,
      "name": "get_segment_selector.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590170771,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:320",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590168176,
      "name": "get_segment_selector.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_segment_selector",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590221219,
      "name": "get_segment_selector",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:320",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:insn_get_code_seg_params"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590218624,
      "name": "get_segment_selector.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
short int get_segment_selector(struct pt_regs * regs, int seg_reg_idx)
```
</details>
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
