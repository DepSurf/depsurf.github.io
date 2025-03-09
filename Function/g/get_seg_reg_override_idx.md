# Function: <code>get_seg_reg_override_idx</code>

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
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588820531,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589198821,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589440165,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589898236,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590124220,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585128533,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
int get_seg_reg_override_idx(struct insn * insn)
```

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585277536,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:93",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/lib/insn-eval.c:get_seg_base_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585277536,
      "name": "get_seg_reg_override_idx",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 257
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
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585162965,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:93",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585616149,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:93",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586773781,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:91",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595939477,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:91",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596457829,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:91",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071597352853,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:91",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589726476,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589452284,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590169852,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "get_seg_reg_override_idx",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590220300,
      "name": "get_seg_reg_override_idx",
      "external": false,
      "loc": "arch/x86/lib/insn-eval.c:69",
      "file": "arch/x86/lib/insn-eval.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
int get_seg_reg_override_idx(struct insn * insn)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int get_seg_reg_override_idx(struct insn * insn)
```
</details>
</li>
</ul>
