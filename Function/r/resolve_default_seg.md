# Function: <code>resolve_default_seg</code>

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
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588820906,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588820208,
      "name": "resolve_default_seg.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 74
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
int resolve_default_seg(struct insn * insn, struct pt_regs * regs, int off)
```

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589198352,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589198352,
      "name": "resolve_default_seg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589440666,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589439824,
      "name": "resolve_default_seg.part.6",
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
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589898773,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589897824,
      "name": "resolve_default_seg.part.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590124757,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590123808,
      "name": "resolve_default_seg.part.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585127392,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585127392,
      "name": "resolve_default_seg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585278592,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:181",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585278592,
      "name": "resolve_default_seg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585162000,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:181",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585162000,
      "name": "resolve_default_seg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585615168,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:181",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585615168,
      "name": "resolve_default_seg.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 213
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586774476,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:179",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595940172,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:179",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596458429,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:179",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597353453,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:179",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589727013,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589726064,
      "name": "resolve_default_seg.part.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589452756,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589451824,
      "name": "resolve_default_seg.part.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590170389,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590169440,
      "name": "resolve_default_seg.part.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "resolve_default_seg",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590220837,
      "name": "resolve_default_seg",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:156",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit",
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590219888,
      "name": "resolve_default_seg.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 82
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
int resolve_default_seg(struct insn * insn, struct pt_regs * regs, int off)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
int resolve_default_seg(struct insn * insn, struct pt_regs * regs, int off)
```
</details>
</li>
</ul>
